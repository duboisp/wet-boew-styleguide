---
published: true
layout: default-theme-wet-boew-en
title: Absolute positioning
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
          <h2 class="panel-title">Table of contents</h2>
        </header>
        <div class="panel-body">
          <ul>
            <li><a href="#purpose">Purpose</a></li>
            <li><a href="#design">Design and coding</a>
              <ul>
                <li><a href="#basic">Basic use</a> </li>
                <li><a href="#enhanced">Enhanced use</a>
                  <ul>
                    <li><a href="#addon">Add-on features</a> </li>
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
          <h2 class="mrgn-tp-0 h4 text-warning"><span class="fa fa-exclamation-triangle"></span> Work in progress</h2>
          <p>This page is a work in progress.</p>
          <p>Please <a href="https://github.com/wet-boew/wet-boew-styleguide/issues/new">file an issue</a> or submit a pull request if information or coding is missing, incorrect or out of sync with the main repository (wet-boew/wet-boew).</p>
        </div>
      </div>
    </section>
  </div>
  <h2 id="purpose"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-info fa-stack-1x fa-inverse"></span></span> Purpose</h2>
  <p>Use  to position  content on top of other content.</p>
  <h2 id="design"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-paint-brush fa-stack-1x fa-inverse"></span></span> Design and coding</h2>
  <h3 id="basic">Basic use</h3>
  <h4 id="default"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-gears fa-stack-1x fa-inverse"></span></span> Default</h4>
  <p>Use to control the content  position on a page. The browser always positions content on the top left. To modify the default placement, both the <var>x</var> and <var>y</var> position <strong>must </strong>be defined. The <var>x</var> positions are <code>pstn-lft-*</code> and <code>pstn-rght-*</code>. The <var>y</var> positions are <code>pstn-tp-*</code> and <code>pstn-bttm-*</code>. Since both <var>x</var> and <var>y</var> positions work together, the posting is responsive. When the grid system linearizes for smaller viewports, so does the positioning.</p>
  <table class="table table-bordered">
  <caption class="wb-inv">Default positioning <abbr title="cascading style sheet">CSS</abbr></caption>
    <thead>
      <tr>
        <th scope="col">Top positioning</th>
        <th scope="col">Right positioning</th>
        <th scope="col">Bottom positioning</th>
        <th scope="col">Left positioning</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><ul class="list-unstyled">
            <li><code>.pstn-tp-xs</code> = always positioned </li>
            <li><code>.pstn-tp-sm</code> = tablets upwards only</li>
            <li><code>.pstn-tp-md</code> = small desktop upwards only</li>
            <li><code>.pstn-tp-lg</code> = large desktop upwards only</li>
          </ul></td>
        <td><ul class="list-unstyled">
            <li><code>.pstn-rght-xs</code> = always positioned</li>
            <li><code>.pstn-rght-sm</code> = tablets upwards only</li>
            <li><code>.pstn-rght-md</code> = small desktop upwards only</li>
            <li><code>.pstn-rght-lg</code> = large desktop upwards only</li>
          </ul></td>
        <td><ul class="list-unstyled">
            <li><code>.pstn-bttm-xs</code> = always positioned</li>
            <li><code>.pstn-bttm-sm</code> = tablets upwards only</li>
            <li><code>.pstn-bttm-md</code> = small desktop upwards only</li>
            <li><code>.pstn-bttm-lg</code> = large desktop upwards only</li>
          </ul></td>
        <td><ul class="list-unstyled">
            <li><code>.pstn-lft-xs</code> = always positioned</li>
            <li><code>.pstn-lft-sm</code> = tablets upwards only</li>
            <li><code>.pstn-lft-md</code> = small desktop upwards only</li>
            <li><code>.pstn-lft-lg</code> = large desktop upwards only</li>
          </ul></td>
      </tr>
    </tbody>
  </table>
  <div class="row">
    <div class="col-md-4">
      <div class="panel panel-default">
        <div class="panel-body">
          <h5 class="mrgn-tp-0">Appearance</h5>
          <div class="row">
            <div class="col-xs-12"> <a href="#"><img src="https://www.canada.ca/content/canadasite/assets/finance/carousel/20141203-1.jpg" class="img-responsive full-width" alt="Image of people and trees">
              <p class="well brdr-rds-0 well-sm mrgn-bttm-sm mrgn-rght-md mrgn-lft-md opct-90 pstn-bttm-xs pstn-rght-xs">Link on top of image</p>
              </a> </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-md-4">
      <h5 class="mrgn-tp-0 text-success"><span class="glyphicon glyphicon-ok-circle"></span> Correct use</h5>
<p>Compliance point(s):</p>
        <ul>
        <li> Use any <abbr title="cascading style sheet">CSS</abbr> property <strong>other than</strong> <code>.static</code> with the layer that's to appear behind the absolute positioned object. For example, grids have a <abbr title="cascading style sheet">CSS</abbr> property of <code>position: relative</code>, so they work well with this design component</li>
        <li> Use to overlay text over an image</li>
        <li> Ensure the image and text relate to each other</li>
      </ul>
      <h5 class="mrgn-tp-0 text-danger"><span class="glyphicon glyphicon-remove-circle"></span> Incorrect use</h5><p>Compliance point(s):</p><ul>
        <li> Do not use this component in a way that conflicts with the preceding compliance <span class="nowrap">point(s)</span></li>
        <li>Do not overlay text over text</li>
        <li> Do not overlay text over an image so that the image is no longer visible</li>
      </ul>
    </div>
    <div class="col-md-4">
      <h5 class="mrgn-tp-0">Code</h5>
      <pre><code>&lt;div class=&quot;row&quot;&gt;
  &lt;div class=&quot;col-xs-12&quot;&gt;
   &lt;a href=&quot;#&quot;&gt;
    &lt;img src=&quot;..&quot; class=&quot;img-responsive full-width&quot; alt=&quot;&quot;&gt;
    &lt;p class=&quot;well brdr-rds-0 well-sm mrgn-bttm-sm mrgn-rght-md mrgn-lft-md opct-90 <strong>pstn-bttm-xs pstn-rght-xs</strong>&quot;&gt;...&lt;/p&gt;
   &lt;/a&gt;
  &lt;/div&gt;
&lt;/div&gt;</code></pre>
    </div>
  </div>
  <h3 id="enhanced">Enhanced use</h3>
  <h4 id="addon"><span class="fa-stack"><span class="fa fa-circle fa-stack-2x"></span><span class="fa fa-stack-1x fa-plus fa-inverse"></span></span> Add-on features</h4>
  <p>Additional add-on features and behaviours are available.</p>
  <ul class="list-inline lst-spcd">
    <li><a class="btn btn-default" href="opacity-en.html">Opacity</a></li>
  </ul>
{% endraw %}
{:/}
