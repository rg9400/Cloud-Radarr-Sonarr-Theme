# Cloud-Radarr-Sonarr-Theme
<h2>Cloud CSS for Radarr and Sonarr</h2>
Credits to <a href="https://github.com/iFelix18/Darkerrr">Darkerr</a>, <a href="https://github.com/gilbN">GilbN</a>, and <a href="https://github.com/leram84">Leram</a> whose work was the base and inspiration for this. 

Radarr and Sonarr give you an easy way to add custom css, so you will need to insert it with your reverse proxy. The below is an example that you can inside your NGINX Tau location block to insert the CSS when accessing via your domain (not locally). You need the subfilter module for it to work. If you don't use nginx or don't have that module, I don't know enough to help out.

```nginx		
			proxy_set_header Accept-Encoding "";
			sub_filter
			'</head>'
			'<link rel="stylesheet" type="text/css" href="https://rawgit.com/rg9400/Cloud-Radarr-Sonarr-Theme/master/CloudArr.css">
			</head>';
			sub_filter_once on;
 ```
 ### Screenshots
<details><summary>Expand</summary>
<p>
Coming Soon
</p>
</details>
