---
layout: default
css: "/css/search.css"
---

**Resultados de uma [pesquisa personalizada google]. Só procura nos nomes
dos arquivos e não no conteúdo deles.**

<div id="google-custom-search">
<script>
  (function() {
    var cx = '006188253788992077998:c_c0es2xw3o';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') +
        '//www.google.com/cse/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script>
<gcse:searchbox></gcse:searchbox>
<gcse:searchresults></gcse:searchresults>
</div>

[pesquisa personalizada google]: https://cse.google.com/cse/
