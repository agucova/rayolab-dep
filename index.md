---
title: Qué Hacemos
layout: page
feature_image: img/background.jpg
published: true
---

El laboratorio de neurobiología y biología del conocer es un laboratorio...

Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Suspendisse sed erat dictum, rutrum dui quis, consequat ante. Donec sollicitudin nunc ac tortor cursus, eu hendrerit diam molestie. Duis ac tincidunt purus. Fusce a mi vel sapien porttitor tristique. Aenean ornare quis ligula non vestibulum. Maecenas euismod lacus eu rutrum feugiat. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Morbi volutpat consectetur nibh quis efficitur. Etiam vestibulum eleifend justo nec tincidunt. Suspendisse ullamcorper nisi ac mi consequat ultrices.

Integer sit amet sem vitae dui interdum pharetra nec quis turpis. Quisque a dui a elit ultricies dapibus. Donec sodales commodo arcu a consectetur. Nullam viverra sollicitudin gravida. Sed suscipit augue in mattis molestie. Nullam tincidunt, nunc vitae egestas porttitor, justo tortor fringilla lorem, ac aliquam turpis arcu sit amet mi. Aenean sagittis viverra nibh vel pretium. Fusce gravida tincidunt urna vel luctus. Sed pulvinar facilisis magna, et imperdiet quam pellentesque ac. Duis id fermentum nisi. Integer sollicitudin posuere laoreet.

## Nuestros Asociados
<ul>
{% for miembro in site.data.miembros %}
  <li>
      <b>{{ miembro.nombre }}</b>: {{ miembro.acerca}}
  </li>
{% endfor %}
</ul>


