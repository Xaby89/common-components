HTML:

<title>Az oldal címe</title>

<h1>A legfontosabb címsor</h1>
<h6>A legkisebb címsor</h6>

<figure>
  <img src="http://a-kep-cime.jpg" rel="alternatív szöveg">
  <figcaption>Képaláírás</figcaption>
</figure>

<article>
  <p>Bekezdés <a href="http://link-valahova.hu" title="A hivatkozott oldal címe>egy kattintható linkkel</a></p>
  <p>Egy másik bekezdés <strong>kiemelten hangsúlyos tartalommal</strong>.</p>
</article>


CSS:

h1 {
  color:          rgba(0,0,0,.8);     // szín, (red, green, blue, opacity (alpha))
  font-family:    serif;              // betûtípus
  font-size:      36px;               // betûméret
  line-height:    1.58;               // sormagasság
  letter-spacing: -.003em;            // betûköz
  text-align:     center;             // szöveg igazítása
}

img {
  height:         auto;               // magasság
  width:          100%;               // szélesség
}

figure {
  margin:         0;                  // margó
}

article {
  margin:         0 auto;             // középre rendezett
}

a:hover {
                                      // az egér éppen ide mutat állapot
}