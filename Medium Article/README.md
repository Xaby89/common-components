HTML:

<title>Az oldal c�me</title>

<h1>A legfontosabb c�msor</h1>
<h6>A legkisebb c�msor</h6>

<figure>
  <img src="http://a-kep-cime.jpg" rel="alternat�v sz�veg">
  <figcaption>K�pal��r�s</figcaption>
</figure>

<article>
  <p>Bekezd�s <a href="http://link-valahova.hu" title="A hivatkozott oldal c�me>egy kattinthat� linkkel</a></p>
  <p>Egy m�sik bekezd�s <strong>kiemelten hangs�lyos tartalommal</strong>.</p>
</article>


CSS:

h1 {
  color:          rgba(0,0,0,.8);     // sz�n, (red, green, blue, opacity (alpha))
  font-family:    serif;              // bet�t�pus
  font-size:      36px;               // bet�m�ret
  line-height:    1.58;               // sormagass�g
  letter-spacing: -.003em;            // bet�k�z
  text-align:     center;             // sz�veg igaz�t�sa
}

img {
  height:         auto;               // magass�g
  width:          100%;               // sz�less�g
}

figure {
  margin:         0;                  // marg�
}

article {
  margin:         0 auto;             // k�z�pre rendezett
}

a:hover {
                                      // az eg�r �ppen ide mutat �llapot
}