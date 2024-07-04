<section>
   <h2>How to run locally on your PC?</h2>
   <ol>
     <li>Clone this repo</li>
     <li> Install Nodejs </li>
     <li> Run "npm start"</li>
     <li> Navigate to  <a>http://localhost:3000/ </a> </li>
   </ol>
  
</section>





<h4>When you initialize an Express server to serve your HTML files, the links within your HTML  depends on the server to function properly. </h4>
<ul>
<li>
Dynamic Content: If your HTML files rely on server-side rendering or dynamic content generation, these will not work properly when just opening the HTML file directly. The server needs to be running to generate and serve the necessary content.  </li>

<li>
Routing: If you're using Express to handle routing, the links within your HTML may depend on the server to resolve different routes. For example, links to /about or /contact would require the server to respond to those routes.
</li>

</ul>

<ul>
  If push is throwing errors you have to "fetch first." use commands:

<li>git fetch origin </li>
Then follow these steps to merge:

<li>git pull origin master </li>
<li>git add .</li>
<li>git commit -m 'your commit message'</li>
<li>git push origin master</li>

</ul>
