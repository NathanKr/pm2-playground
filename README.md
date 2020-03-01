<h2>Introduction</h2>
pm2 is a process manager for node applications on production


<h2>Usage</h2>>
pm2 start server.js (make sure it is installed globally)

<h2>end points</h2>
<ul>
<li>/ - send back html</li>
<li>/api1 - send back status code 200</li>
<li>/api2 - cause server crash but pm2 will respawn the process</li>
</ul>