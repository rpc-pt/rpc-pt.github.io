Para alterar as postagens do instagram, siga os passos abaixo:

Altere ambos os links que aparecem abaixo no arquivo `index.html`, próximos às linhas 2782:

```html
<div class="instagram-post">
    <blockquote class="instagram-media"
        data-instgrm-permalink="https://www.instagram.com/p/DJMzFLwMRaC/" data-instgrm-version="14">
        <div style="padding: 2rem; text-align: center;">
            <a href="https://www.instagram.com/p/DJMzFLwMRaC/" target="_blank"
                style="color: var(--primary-orange); text-decoration: none;">
                <i class="fab fa-instagram"
                    style="font-size: 3rem; margin-bottom: 1rem; display: block;"></i>
                <p style="color: var(--text-on-light);">Ver no Instagram</p>
            </a>
        </div>
    </blockquote>
</div>
<div class="instagram-post">
    <blockquote class="instagram-media"
        data-instgrm-permalink="https://www.instagram.com/p/DJMymnlsyXw/" data-instgrm-version="14">
        <div style="padding: 2rem; text-align: center;">
            <a href="https://www.instagram.com/p/DJMymnlsyXw/" target="_blank"
                style="color: var(--primary-orange); text-decoration: none;">
                <i class="fab fa-instagram"
                    style="font-size: 3rem; margin-bottom: 1rem; display: block;"></i>
                <p style="color: var(--text-on-light);">Ver no Instagram</p>
            </a>
        </div>
    </blockquote>
</div>
```

Ou seja, imagina que quero passar a exibir a postagem "XPTO" do instagram, cujo link é `https://www.instagram.com/p/XPTO12345/`, eu alteraria o código acima para:

```html
<div class="instagram-post">
    <blockquote class="instagram-media"
        data-instgrm-permalink="https://www.instagram.com/p/XPTO12345/" data-instgrm-version="14">
        <div style="padding: 2rem; text-align: center;">
            <a href="https://www.instagram.com/p/XPTO12345/" target="_blank"
                style="color: var(--primary-orange); text-decoration: none;">
                <i class="fab fa-instagram"
                    style="font-size: 3rem; margin-bottom: 1rem; display: block;"></i>
                <p style="color: var(--text-on-light);">Ver no Instagram</p>
            </a>
        </div>
    </blockquote>
</div>
<div class="instagram-post">
    <blockquote class="instagram-media"
        data-instgrm-permalink="https://www.instagram.com/p/DJMzFLwMRaC/" data-instgrm-version="14">
        <div style="padding: 2rem; text-align: center;">
            <a href="https://www.instagram.com/p/DJMzFLwMRaC/" target="_blank"
                style="color: var(--primary-orange); text-decoration: none;">
                <i class="fab fa-instagram"
                    style="font-size: 3rem; margin-bottom: 1rem; display: block;"></i>
                <p style="color: var(--text-on-light);">Ver no Instagram</p>
            </a>
        </div>
    </blockquote>
</div>
```

Lembre-se, é claro, de atualizar o segundo link também para sempre exibir as duas últimas postagens.