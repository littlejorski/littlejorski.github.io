# littlejorski.github.io
A unblock game website
<html><head>
  <style>body,html,iframe{margin:0;padding:0;height:100%;width:100%;overflow:hidden}.forceIosScrolling{overflow:scroll;-webkit-overflow-scrolling:touch}</style>
<script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.yTSbWrSe458.O/m=gapi_rpc/rt=j/sv=1/d=1/ed=1/rs=AHpOoo_5dpdVCMe_LPx1yH-hHA2M85TB-Q/cb=gapi.loaded_0?le=scs" async=""></script><script src="https://apis.google.com/js/api.js?checkCookie=1" gapi_processed="true"></script></head>

<body>
<iframe id="innerFrame" name="innerFrame" sandbox="allow-scripts allow-popups allow-forms allow-same-origin allow-popups-to-escape-sandbox allow-downloads" frameborder="0" allowfullscreen="" src="https://1v1.lol/" style="overflow: auto;">
</iframe>

<script>function loadGapi(){var loaderScript=document.createElement('script');loaderScript.setAttribute('src','https://apis.google.com/js/api.js?checkCookie=1');loaderScript.onload=function(){this.onload=function(){};loadGapiClient();};loaderScript.onreadystatechange=function(){if(this.readyState==='complete'){this.onload();}};(document.head||document.body||document.documentElement).appendChild(loaderScript);}function updateInnerFrame(url,enableInteraction,forceIosScrolling){var urlEl=document.createElement('a');urlEl.setAttribute('href',url);if(urlEl.protocol!="https:"&&urlEl.protocol!="http:"){return;}var iframe=document.getElementById('innerFrame');iframe.src=url;iframe.onload=function(){gapi.rpc.call('..','innerFrameLoaded');};if(enableInteraction){if(forceIosScrolling){var iframeParent=iframe.parentElement;iframeParent.classList.add('forceIosScrolling');}else{iframe.style.overflow='auto';}}else{iframe.style.pointerEvents='none';}}function updateInnerIframeCode(userCode,enableInteraction,forceIosScrolling){gapi.rpc.setup('innerFrame');gapi.rpc.call('innerFrame','updateUserHtmlFrame',undefined,userCode,enableInteraction,forceIosScrolling);}function onPostMessage(ev){if(ev.data['magic']!='SHIC'){return;}var type=ev.data['type'];switch(type){case'resize':var height=ev.data['height'];gapi.rpc.call('..','resize',undefined,height);}}function onGapiInitialized(){gapi.rpc.call('..','gapiInitialized');gapi.rpc.register('updateInnerFrame',updateInnerFrame);gapi.rpc.register('updateInnerIframeCode',updateInnerIframeCode);window.addEventListener('message',onPostMessage);}function loadGapiClient(){gapi.load('gapi.rpc',onGapiInitialized);}if(document.readyState=='complete'){loadGapi();}else{self.addEventListener('load',loadGapi);}</script>


</body></html>
