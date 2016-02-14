# Site da comunidade Pyladies Rio

##Para adicionar uma lady há duas formas:

1) Com redirecionamento externo:
Basta criar um arquivo .md no diretório _ladies com o formato:
```
---
layout: post
title: Nome da Lady
img: /img/ladies/lady.jpg (aponta o caminho da imagem na pasta img/ladies)
redirect: http://sitedalady.com (a URL do site da lady)
---
```

2) Com as informações no próprio site
Basta criar um arquivo .md no diretório _ladies com o formato:
```
---
layout: post
title: Nome da Lady
---
```

```
 <div class="img_row">
  <img class="col three" src="/img/ladies/lady.jpg"> (aponta o caminho da imagem na pasta img/ladies)
 </div>
(Aqui embaixo vai o texto sobre a lady)
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis vitae iaculis orci, id suscipit dui. Nunc congue arcu quis pulvinar eleifend. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Donec at dolor nulla. Quisque id placerat felis. Donec accumsan, magna id egestas vulputate, mi risus sagittis libero, id dapibus urna eros et ante. Vestibulum posuere leo ligula, eget sagittis turpis pretium laoreet. Curabitur quis tellus eget risus ultricies iaculis. Curabitur mollis nisi dolor, sit amet vehicula quam fringilla quis. Vivamus scelerisque eros nec mauris faucibus, ut rutrum enim sollicitudin. Donec ac tempor tortor. Nam vitae hendrerit lectus, vitae dictum tellus.
```
