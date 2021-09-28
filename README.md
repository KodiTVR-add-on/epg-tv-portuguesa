# <a href="#EPG-para-televisão-portuguesa">#EPG-para-televisão-portuguesa</a>
<p>Exemplo de utilização:</p>
&lt;channel id=&quot;RTP 1&quot;&gt;
&lt;display-name lang=&quot;pt&quot;&gt;RTP 1 HD
&lt;/display-name&gt;
&lt;url&gt;http://www.nos.pt
&lt;/url&gt;
&lt;/channel&gt;">
<pre><code># exemplo de canal no ficheiro .xml



&lt;channel id="RTP 1"&gt;
&lt;display-name lang="pt"&gt;RTP 1 HD
&lt;/display-name&gt;
&lt;url&gt;http://www.nos.pt
&lt;/url&gt;
&lt;/channel&gt;
</code></pre></div>
<p>Utilizando um exemplo de lista IPTV, basta que no campo "tvg-id" ou o campo do nome do canal seja igual ao "channel id", para que a grelha apareça corretamente para um determinado canal.</p>
<div class="snippet-clipboard-content position-relative" data-snippet-clipboard-copy-content="#EXTM3U
#EXTINF:-1 tvg-id=&quot;RTP 1&quot;,NOME DO CANAL QUE QUISEREM
http://null
"><pre><code>#EXTM3U
#EXTINF:-1 tvg-id="RTP 1",NOME DO CANAL QUE QUISEREM
http://null
</code></pre></div>
<h1><a id="user-content-utilização" class="anchor" aria-hidden="true" href="#utilização"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Utilização</h1>
<p>O link a colocar na parte de epg pode ser o seguinte: <a href="https://bit.ly/39Fo8SZ" rel="nofollow">https://bit.ly/39Fo8SZ</a></p>
<p>Qualquer dúvida ou canais que queiram adicionados/removidos, façam pedido!</p>
