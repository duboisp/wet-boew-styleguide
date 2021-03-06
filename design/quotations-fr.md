---
published: true
layout: default-theme-wet-boew-fr
title: Citations
hide_breadcrumb: false
modified: 2019-04-11
---
{::nomarkdown}
{% raw %}
  <span class="wb-prettify all-pre"></span>
  <div class="row">
    <nav role="navigation" class="col-md-8">
      <div class="panel panel-default">
        <header class="panel-heading">
          <h2 class="panel-title">Table des matières</h2>
        </header>
        <div class="panel-body">
          <ul>
            <li><a href="#purpose">Usage</a></li>
            <li><a href="#design">Conception et codage</a>
              <ul>
                <li><a href="#basic">Utilisation de base</a>
                  <ul>
                    <li><a href="#blockquote">Blockquote</a></li>
                    <li><a href="#cite">Citer une source</a></li>
                    <li><a href="#inline">Citations incorporées</a></li>
                  </ul>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="col-md-4">
      <div class="panel panel-warning">
        <div class="panel-body">
          <h2 class="mrgn-tp-0 h4 text-warning"><span class="fa fa-exclamation-triangle"></span> Chantier</h2>
          <p>Cette page est en chantier.</p>
          <p>Veuillez <a href="https://github.com/wet-boew/wet-boew-styleguide/issues/new">transmettre un problème</a> ou soumettre une demande de tirage s'il manque des renseignements ou des codes ou si la synchronisation est incorrecte ou déphasée avec le principal référentiel (wet-boew/wet-boew).</p>
        </div>
      </div>
    </section>
  </div>
  <h2 id="purpose"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-info fa-stack-1x fa-inverse"></span></span> Usage</h2>
  <p>Utilisez les citations pour reprendre un groupe de mots prononcés par quelqu'un d'autre que l'auteur ou le conférencier d'origine.</p>
  <h2 id="design"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-paint-brush fa-stack-1x fa-inverse"></span></span> Conception et codage</h2>
  <h3 id="basic">Utilisation de base</h3>
  <p>L'utiliser pour citer des blocs de contenu venant d'une autre source à l'intérieur de votre document.</p>
  <section>
    <h4 id="blockquote"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-quote-left fa-stack-1x fa-inverse"></span></span> Blockquote</h4>
    <p>L'utiliser pour indiquer une<strong> longue citation </strong>de texte qui provient d'une autre source.</p>
    <div class="row">
      <div class="col-md-3">
        <div class="panel panel-default">
          <div class="panel-body">
            <h5 class="mrgn-tp-0">Apparence</h5>
            <p>Classe « blockquote » par défaut :</p>
			<blockquote>

              <p>Le texte va ici.</p>
            </blockquote>
			<p>Classe « blockquote-reverse » :</p>
            <blockquote class="blockquote-reverse">
              <p>Le texte va ici.</p>
            </blockquote>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <h5 class="mrgn-tp-0 text-success"><span class="glyphicon glyphicon-ok-circle"></span> Bonne utilisation</h5>
<p><span class="nowrap">Points de conformité&nbsp;:</span></p>
        <ul>
          <li>Entourez de <code>&lt;blockquote&gt;</code> les citations qui<strong> font plus que quelques mots</strong></li>
          <li>Utilisez <code>&lt;p&gt;</code> à l'intérieur de  <code>&lt;blockquote&gt;</code></li>
          <li>Utilisez <code>.blockquote-reverse</code> pour une classe « blockquote » avec flottement et alignement à droite</li>
        </ul>
        <h5 class="mrgn-tp-0 text-danger"><span class="glyphicon glyphicon-remove-circle"></span> Mauvaise utilisation</h5><p><span class="nowrap">Points de conformité&nbsp;:</span></p><ul>
          <li>N'utilisez pas cet élément d'une façon qui entre en conflit avec les points de conformité précédents</li>
          <li><strong>N'ajoutez pas de guillemets </strong>(<strong>&quot;</strong>) (<code>&amp;quot;</code>) ou d'images de guillemets au texte, puisqu'il s'agit là d'un style redondant</li>
          <li>Ne l'utilisez pas si vous pouvez établir un lien direct avec le contenu source</li>
          <li>Ne l'utilisez pas si vous pouvez reformuler le contenu dans un langage clair et simple et de manière concise</li>
          <li>Ne l'utilisez pas pour mettre en forme du contenu qui n'est pas une citation</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5 class="mrgn-tp-0">Code</h5>
        <pre><code>// Classe « blockquote » par défaut :<strong>
&lt;blockquote&gt;</strong>
  <strong>&lt;p&gt;</strong>...&lt;/p&gt;
&lt;/blockquote&gt;

// Classe « blockquote » avec alignement à droite :
&lt;blockquote <strong>class=&quot;blockquote-reverse&quot;</strong>&gt;
  &lt;p&gt;...&lt;/p&gt;
&lt;/blockquote&gt;
</code>
</pre>
      </div>
    </div>
    <h4 id="cite"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="glyphicon glyphicon-user fa-stack-1x fa-inverse"></span></span> Citer une source</h4>
    <p>L'utiliser pour préciser l'auteur du contenu, ainsi que le titre de la source. </p>
    <div class="row">
      <div class="col-md-4">
        <div class="panel panel-default">
          <div class="panel-body">
            <h5 class="mrgn-tp-0">Apparence</h5>
			<p>Classe « blockquote » avec le pied de page par défaut :</p>
			<blockquote>
              <p>Le texte va ici.</p>
              <footer>Nom de l'auteur<br>
                <cite>Titre de la source du contenu citée</cite></footer>
            </blockquote>
			<p>Classe « blockquote » avec pied de page aligné à droite :</p>
            <blockquote>
              <p>Le texte va ici.</p>
              <footer class="text-right">Nom de l'auteur<br>
                <cite>Titre de la source de contenu citée</cite></footer>
            </blockquote>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <h5 class="mrgn-tp-0 text-success"><span class="glyphicon glyphicon-ok-circle"></span> Bonne utilisation</h5>
<p><span class="nowrap">Points de conformité&nbsp;:</span></p>
        <ul>
          <li>Dans la mesure du possible, indiquez la source de la citation à l'aide de  <code>&lt;footer&gt;</code> (nom de l'auteur) et <code>&lt;cite&gt;</code> (titre de la source)</li>
          <li>Utilisez <code>&lt;br&gt;</code> pour placer le titre de la source citée sous le nom de l'auteur</li>
          <li>Mettez une majuscule au titre de la source citée  <strong>de la même façon que le fait l'auteur</strong></li>
        </ul>
        <h5 class="mrgn-tp-0 text-danger"><span class="glyphicon glyphicon-remove-circle"></span> Mauvaise utilisation</h5><p><span class="nowrap">Points de conformité&nbsp;:</span></p><ul>
          <li>N'utilisez pas cet élément d'une façon qui entre en conflit avec <span class="nowrap">les points</span>  d'observation  <span class="nowrap">précédents</span></li>
          <li>N'omettez pas la source de la citation</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5 class="mrgn-tp-0">Code</h5>
        <pre><code>// Pied de page par défaut :
 &lt;blockquote&gt;
   &lt;p&gt;...&lt;/p&gt;
   <strong>&lt;footer&gt;</strong>Nom de l'auteur<strong>&lt;br&gt;</strong>
    <strong>&lt;cite&gt;</strong>Titre de la source du contenu citée&lt;/cite&gt;
  &lt;/footer&gt;
&lt;/blockquote&gt;

// Pied de page aligné à droite :
&lt;blockquote&gt;
  &lt;p&gt;...&lt;/p&gt;
  <strong>&lt;footer class=&quot;text-right&quot;&gt;</strong>Nom de l'auteur<strong>&lt;br&gt;</strong>
    <strong>&lt;cite&gt;</strong>Titre de la source du contenu citée&lt;/cite&gt;
 &lt;/footer&gt;
&lt;/blockquote&gt;</code></pre>
      </div>
    </div>
    <h4 id="inline"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-stack-1x fa-inverse">-&ldquo;-</span></span> Citations incorporées</h4>
    <p>Utilisez les citations intégrées pour les extraits de contenu qui sont cités d'une autre source. Elles apparaissent  <strong>à l'intérieur d'une phrase</strong>. </p>
    <div class="row">
      <div class="col-md-3">
        <div class="panel panel-default">
          <div class="panel-body">
            <h5 class="mrgn-tp-0">Apparence</h5>
            <p>Phrase complète avec le deux-points : "<q>Phrase citée!</q>"</p>
            <p>Déclaration de quelqu'un ou expression introductive, &quot;section de texte cité.&quot; </p>
            <p>Déclaration de quelqu'un ou expression introductive, &quot;Phrase citée.&quot; </p>
            <p>Expression introductive,   &quot;section du texte cité qui nécessite maintenant une virgule,&quot; texte texte texte. </p>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <h5 class="mrgn-tp-0 text-success"><span class="glyphicon glyphicon-ok-circle"></span> Bonne utilisation</h5>
<p><span class="nowrap">Points de conformité&nbsp;:</span></p>
        <ul>
          <li>Utilisez une citation incorporée si la citation a <strong>moins de quelques mots de longueur</strong></li>
          <li>Utilisez les doubles guillemets (<strong>&quot;</strong>) (<code>&amp;quot;</code>) pour les citations incorporées</li>
          <li>Enveloppez la citation dans des guillemets  <strong>et</strong> l'élément <code>&lt;q&gt;</code></li>
          <li>Placez les points et les virgules<strong> à l'intérieur </strong> de la balise fermante <code>&lt;/q&gt;</code>
              <ul>
              <li>Il s'agit du style que l'<abbr title="Agence du revenu du Canada">ARC</abbr> utilise pour les guillemets</li>
              <li>À moins qu'ils fassent partie de la citation originale, placez tous les autres signes   <strong>à l'extérieur</strong> des guillemets</li>
            </ul>
          </li>
        </ul>
        <h5 class="mrgn-tp-0 text-danger"><span class="glyphicon glyphicon-remove-circle"></span> Mauvaise utilisation</h5><p><span class="nowrap">Points de conformité&nbsp;:</span></p><ul>
          <li>N'utilisez pas cet élément d'une façon qui entre en conflit avec <span class="nowrap">les points</span>  d'observation  <span class="nowrap">précédents</span></li>
          <li>Ne l'utilisez pas si vous pouvez reformuler le contenu dans un langage clair et simple et de manière concise</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5 class="mrgn-tp-0">Code</h5>
        <pre><code>
// Phrase complète avec le deux-points, puis la citation :
<strong>&lt;p&gt;</strong>Complete sentence<strong>:</strong> <strong>&amp;quot;&lt;q&gt;Quoted sentence!&amp;quot;&lt;/q&gt;&lt;/p&gt;</strong>

// Déclaration de quelqu'un ou expression introductive, puis citation :
&lt;p&gt;...<strong>, &amp;quot;&lt;q&gt;...&amp;quot;&lt;/q&gt;</strong>&lt;/p&gt;

// Déclaration de quelqu'un ou expression introductive, citation qui nécessite maintenant une virgule :
&lt;p&gt;...<strong>, &amp;quot;&lt;q&gt;...,&amp;quot;&lt;/q&gt; </strong>...&lt;/p&gt;</code></pre>
      </div>
    </div>
    <p class="mrgn-tp-lg">Utilisez-le pour préciser un titre, un bouton ou une action qui n'est pas un lien.</p>
    <div class="row">
      <div class="col-md-3">
        <div class="panel panel-default">
          <div class="panel-body">
            <h5 class="mrgn-tp-0">Apparence</h5>
            <p>Ensuite, sélectionnez le bouton « Ouvrir une session ». </p>
          </div>
        </div>
      </div>
      <div class="col-md-5">
        <h5 class="mrgn-tp-0 text-success"><span class="glyphicon glyphicon-ok-circle"></span> Bonne utilisation</h5>
<p><span class="nowrap">Point d'observation&nbsp;:</span></p>
        <ul>
          <li>Utilisez les guillemets pour préciser un <strong>titre</strong>, un <strong> bouton</strong> ou une<strong> action</strong> qui<strong> n'est pas autour ou à l'intérieur d'un lien</strong></li>
        </ul>
        <h5 class="mrgn-tp-0 text-danger"><span class="glyphicon glyphicon-remove-circle"></span> Mauvaise utilisation</h5><p><span class="nowrap">Points de conformité&nbsp;:</span></p><ul>
          <li>N'utilisez pas cet élément d'une façon qui entre en conflit avec <span class="nowrap">les points</span>  d'observation  <span class="nowrap">précédents</span></li>
          <li>N'entourez pas un lien de guillemets</li>
          <li>Ne l'utilisez pas si vous pouvez reformuler le contenu dans un langage clair et simple et de manière concise</li>
        </ul>
      </div>
      <div class="col-md-4">
        <h5 class="mrgn-tp-0">Code</h5>
        <pre><code>&lt;p&gt;... <strong>&amp;quot;...&amp;quot;</strong> ...&lt;/p&gt;</code></pre>
      </div>
    </div>
  </section>
{% endraw %}
{:/}
