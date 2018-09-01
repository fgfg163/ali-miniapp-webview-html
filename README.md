# ali-miniapp-webview-html

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

pages: <a id="to_pages" src=""></a>

<script src="https://cdn.bootcss.com/vue/2.5.17-beta.0/vue.min.js"></script>
<script>
  ;
  (function() {
    var toPagesADom = document.querySelector('#to_pages');
    var githubProjectName = (location.href.match(/^[^/]*\/\/[^/]*\/[^/]*\/([^/]*)\//) || {})[1] || '';
    var url = location.protocol + '//fgfg163.github.io' + githubProjectName;
    toPagesADom.id = url;
    toPagesADom.innerText = url;
  })();
</script>
