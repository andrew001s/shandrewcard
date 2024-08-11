# Links de Redes Sociales
Proyecto para almacenar distintas redes sociales en una sola página personalizada 

# Cambios Links
Si quieres cambiar los enlaces, dentro del archivo index.html podras encontrar los siguientes elementos:

```html
   <a href="https://twitch.tv/elshandrew" target="_blank">
                        <div class="twitch">
                            <i class="bi bi-twitch "> Twitch</i>

                        </div>
    </a>
```

Cambia el valor del href con el link a tu perfil de la red social.

# Cambios iframe:

Para esto te recomiendo usar: https://livecounts.io/ , aqui encontraras iframes para cada distinta red social, busca tu perfil
en la parte baja del sitio encontraras el codigo embebido para el iframe, copialo y reemplazalo dentro de index.html:

```html
<iframe height="80px" width="300px" frameborder="0"
                    src=https://livecounts.io/embed/tiktok-live-follower-counter/elshandrew
                    style="border-radius: 15px; width:300px; height:80px;">
</iframe>
```

# Preview:
https://shandrewcard.netlify.app/

Te recomiendo desplegarlo con githubPages o con netlify.



