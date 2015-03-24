<!--兼容版，可保证页面完全兼容-->
<div id="SOHUCS" sid="{{ page.uuid }}"></div>
<script>
  (function(){
    var appid = 'cyrGKwcKP',
    conf = 'prod_1debb5cf907063111dab87a8c61569f6';
    var doc = document,
    s = doc.createElement('script'),
    h = doc.getElementsByTagName('head')[0] || doc.head || doc.documentElement;
    s.type = 'text/javascript';
    s.charset = 'utf-8';
    s.src =  'http://assets.changyan.sohu.com/upload/changyan.js?conf='+ conf +'&appid=' + appid;
    h.insertBefore(s,h.firstChild);
  })()
</script>

               
