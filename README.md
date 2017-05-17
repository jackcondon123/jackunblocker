# jackunblocker
hi
<html><head>
  <title>Node Unblocker</title>
  <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport">
  <!-- header font -->
  <link href="http://fonts.googleapis.com/css?family=Orbitron" rel="stylesheet" type="text/css">
  
  <!-- body font -->
  <link href="http://fonts.googleapis.com/css?family=Droid+Sans" rel="stylesheet" type="text/css">
  
  <style type="text/css">
	
    /* fonts */
    body { font-family: 'Droid Sans', arial, serif;  letter-spacing: 1px;}
    h1 { font-family: 'Orbitron', arial, serif; letter-spacing: 2px;}
    h2, h3, h4, h5, h6 { letter-spacing: 2px; font-weight: normal;}
  
    /* colors */
    body { background-color: #000306; color: white;}
    .container { background-color: #3F4038; border-color: #5B3E38}
    a { color: #62BECB; }
    a:hover {color: #82DEEB }

	#error {  border:1px dotted white; background: brown; }
    
    /* stripes and borders */
    
    .main { background-repeat: repeat-x;  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAB9CAIAAADbWVFQAAADd0lEQVR4nO3d6VbbMBiE4Tcm3Tf2tRfSf+393wd03/dCk/6AgjF2otiSvpGsuYBY52HO4JPEMHn+4hl6eTqzPkFbptYHaMnRjLn1GW7muKKyPkMzR5KdOq4AMSxlKaSwxKXQ2axDyZ06ud4liWYdSnbq5IaNPVYqUphjJSSF7WYdSO7Uy+7+mDXrQLJTC6SwwkpRChOsRKWIj5WuFJEHfl9y0V85FyZes/YlO+UuRTSsDKSIg5WHFBE2a09yp173KknYZu1JdqqfFEGxMpMiHFZ+UgTCylKKEAO/K7nob3y0wnOzdiU75UUKv1h5S+ERK3spfG3WjuROvfX928vD6+1Idsq7FMOxxiPFQKxRSTEEa2xS9B74bclFfxf4Dac+L78t2anQUvTAGq0Uq2KNWYqVNmtLcqfeR/wwz/VSW5KdiimFI1aROs/yCxapyyy5ZpGqZ9HAb0ou+ge77991XnlTslOGUnRhFanWtFy/SHWluVkbkjv1UUCKRrM2JDslIkUdq0gtzcVZipRLKoqUc6brkov+SU8K88dRWqMptT7Tw5KVQq1ZylLAVGewPktKPaltusoBZaXqkThjElIoYKUihTlWQlLYDvwXSanH3XfpZueVlVoQmyOnKIUJVqJSwHQ+CX+QWr7GvZxjHs1xcYj6U5aVckw8rNSliIaVgRRx7rO+SUo9nK/8rmfwZslK9UhYrJykCIqVmRThsPKTItDAf5eUerD6ojfiv1myUsPjGStjKfxi5S2Fx836ISl1f/BO1eOnWbJSfuMBayRSDMcajxQDsUYlxZCB/ykpdc/rojfSs1myUkHTB2ucUvTAGq0Uq27WL0mpuyF3qp4VmiUrFS2uWEUKR6widZ7lWEXqMksG/rek1J1Yi97IombJSlmlE6tI3Uw7VpFqTctm/ZGUum20U/U0myUrpZBrWEVqca6witTSXGAVKZdM53AqKXVLYNEbqWSlBKP4NWtNqdOJHpasFDr/OfM8U72dAs7+L5VQs4Qeqq3lrLbpKlj6UohgJSGFAlYqUpgP/Jrkov/tuPe0bNaaoFO3FIZYyUlhhZWiFCabVUnu1Ezt4UygEnRykyIyVtJSxMRKXYpoWBlIEWfgJ5KL3uPPDgRv1kTQqZcUobFykiIoVmZSBNwsyZ1i2KczYZql6DRUiiBYmUrhHytfKeAfdPYd7TpexlgAAAAASUVORK5CYII=); }
    .footer { min-height: 60px; background-repeat: repeat-x; background-position: bottom left; background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGQAAAA8CAIAAAAfXYiZAAAB+ElEQVR4nO3b11aDQBSF4T2IXWM3lhfxTt//PWKvsTfwIllLEobQZuZsYM4DyFkffyKBRJ2encBPsQmlF9BNHEtvoBul+LBiAEp6idQogK0sRdlUrMYnjwhLUTYVJzZiwQoom4rUxMmjwAoom4pSG8ljzTEmhV/duQucrzExDZKCbFkhpdRP9vuBWFmNk4JUWfOUUt95/2MEymqoFNyXtUAp9VXsusVpWY2WgsuyFimlPstcCzsqqwVScIPVDik4eBkuUUp9VPokaresNknBalnLlFLvNe5u2CqrfVKwVNYKpdRb7Ttm5stqqxSMl7VKKfVq6C6sybLaLQWDZa1RSr0YvbNvpqwuSMFIWeuUUs8WnhbVLas7UqhZVo9SamjtCWR1rF5kcA1jM7T5Ybfi3+6gFKqVtUEp9WT/1lzpI3RWCmXL2qSUenT11KXEcTouheJlbVFKPbh9RlzoaF5qNPllbVNK3Ut8oyXnmF4qObPK2qGUupP7/l3mkb1UevRl7VJK3Qp/p1NXlpfKmumy9iilbgikMFWWl5o9/4t4qdwZvwz3KaWumaQwKstLFZywTyl1xScF8Z+jaIdTqh8hZPsx1iWl1EEEsJXFLAUwlXVBKXWYeE9nWZBfCiRlnVNKHaWuE+TXbIoUxMsaUEodZ1x7Si7bLCkAf1M7eHbSdYGuAAAAAElFTkSuQmCC); }
    .container { border-style: solid; border-width: 1px; border-radius: 10px;  -moz-border-radius: 10px;  -webkit-border-radius: 10px;  overflow:hidden;  /* otherwise the background image appears on top of the curved border */ }
    
    
    /* layout */
    body { text-align: center; }
    .container { width: 760px; margin: 40px auto; text-align: left;  max-width: calc(100% - 10px);}
    
    h2, h3, h4, h5, h6 { margin-bottom: 0;  }
    ul { line-height: 150%; }
    ul, p {  margin-top: 5px; margin-bottom: 0; }
    .main, .footer { padding: 1px 10px 0 10px; }
    
    #error {display: none; padding: 5px 10px; margin: 30px 10px; }
    
    form ul { list-style-type: none; padding-left: 25px;}
    
    .footer { position: relative; clear: both;}
    .footer p { margin:0; position: absolute; bottom: 10px;  right: 10px; padding-left: 10px; }
    
    #google-ad {
        text-align: center;
        margin: 10px auto;
    }
    @media(min-width: 768px) {        
		#google-ad {
            margin: 0;
            float:right; 
            margin:4px 2px 2px 20px;
        }
    }
	@media(max-width: 768px) {
        .container {
		width:100%;
		}               
    } 
  </style>
</head>
<body>

  <div class="container">
  
    <div class="main">
  
      <h1>Node Unblocker</h1>
      
      <div id="error"></div>

      <form action="/proxy/no-js" method="get" id="unblocker-form" novalidate="">
         <div class="link-form" style="padding-left: 45px;padding-right: 45px;position: relative;">
          <div style="position: absolute;top: 5px;left: 0;">URL: </div> 
          <input type="url" id="url" name="url" autofocus="autofocus" novalidate="true" style="width: 100%;">
          <input type="submit" value="Go" style="position: absolute;top: 0;right: 0;">
        </div>

      </form>
      
<div id="google-ad">
<script type="text/javascript" async="" src="http://www.google-analytics.com/ga.js"></script><script async="" src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- nodeunblock -->
<ins class="adsbygoogle" style="display:inline-block;width:336px;height:280px" data-ad-client="ca-pub-7501280081344007" data-ad-slot="2620395391"></ins>
<script>
(adsbygoogle = window.adsbygoogle || []).push({});
</script>
</div>
      
      <h3>About Node Unblocker</h3>
      <p>Node Unblocker is a web proxy, similar to CGIProxy, PHProxy, or Glype, that alows users to evade filters and unblock blocked sites. </p>
      <p>It's designed to be extremely fast and compatible: It processes the data on-the-fly rather than buffering the entire response, and it only modifies URLs when necessary - relative ones will "just work". </p>
		<p>NodeUnblock.com support <a href="https://nodeunblock.herokuapp.com/proxy">SSL/TLS</a> secure connections. Secure web browsing sessions.</p>

    </div>
    
    <div class="footer">
      <p><a href="https://nodeunblock.com/proxy">Node Unblock</a> v0.12.1 by <a href="https://plus.google.com/+Nodeunblock" title="Node.js developer and JavaScript Expert">Andrew Le</a></p>
    </div>
  
  </div>
	<script>
		function $(id){
			return document.getElementById(id);
		}

		var l = window.location

		var baseUrl = l.hostname == "nodeunblocker.com" ?
		     "https://node-unblocker.herokuapp.com/proxy/" : 
		     l.protocol + '//' +  l.host + '/proxy/';

		$('unblocker-form').onsubmit = function(){
			var url = $('url').value;
			if(url.substr(0,4) != "http"){
				url = "http://" + url;
			}
			window.location = baseUrl + url;
			return false;
		}
