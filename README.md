# Cloud-Radarr-Sonarr-Theme
<h2>Cloud CSS for Radarr and Sonarr</h2>
Credits to <a href="https://github.com/iFelix18/Darkerr">Darkerr</a>, <a href="https://github.com/gilbN">GilbN</a>, and <a href="https://github.com/leram84">Leram</a> whose work was the base and inspiration for this. 

 ### Setup
<details><summary>Expand</summary>
<p>
Radarr and Sonarr don't give you an easy way to add custom css, so you will need to insert it with your reverse proxy. The below is an example that you can inside your NGINX Sonarr and Radarr location blocks to insert the CSS when accessing via your domain (not locally). You need the subfilter module for it to work. If you don't use nginx or don't have that module, I don't know enough to help out.

```nginx		
			proxy_set_header Accept-Encoding "";
			sub_filter
			'</head>'
			'<link rel="stylesheet" type="text/css" href="https://rg9400.github.io/CloudThemes/CloudArr.css">
			</head>';
			sub_filter_once on;
 ```
 </p>
</details>

 ### Screenshots
<details><summary>Expand</summary>
<p>

<img src="/Screenshots/CloudArrSS7.png"></img>
<img src="/Screenshots/CloudArrSS8.png"></img>
<img src="/Screenshots/CloudArrSS1.png"></img>
<img src="/Screenshots/CloudArrSS3.png"></img>
<img src="/Screenshots/CloudArrSS4.png"></img>
<img src="/Screenshots/CloudArrSS5.png"></img>

</p>
</details>
