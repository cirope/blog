---
layout: post
title:  Primer artículo
date:   2014-04-15 12:02:42
categories: general
---

Todos los artículos están en el directorio `_posts`. Para agregar nuevos artículos agregue un archivo con el formato: <kbd>AAAA-MM-DD-nombre-del-articulo.markdown</kbd>

También puede resaltar código como sigue:

{% highlight ruby %}
def saludar(nombre)
  puts "Hola #{nombre}"
end
saludar('Franco')
#=> Imprime 'Hola Franco' en STDOUT.
{% endhighlight %}

Para más información revise la documentación de [Jekyll][jekyll].

[jekyll]: http://jekyllrb.com
