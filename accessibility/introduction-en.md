---
published: true
layout: default-theme-wet-boew-en
title: Introduction To WCAG 2.0
hide_breadcrumb: false
modified: 2019-04-11
---
{::nomarkdown}
{% raw %}
<div class="row">
	<nav role="navigation" class="col-md-8">
		<div class="panel panel-default">
			<div class="panel-heading">
				<h2 class="panel-title">Table of contents</h2>
			</div>
			<ul class="mrgn-tp-md">
				<li><a href="#ov">Overview</a></li>
				<li><a href="#cfrm">Conformance requirements</a></li>
				<li><a href="#links">Related links</a></li>
			</ul>
		</div>
	</nav>
</div>
<h2 id="ov" class="page-header">Overview</h2>
<div class="row">
	<div class="col-md-6">
		<p>The <a href="http://www.w3.org/TR/WCAG20/" rel="external"><em>Web Content Accessibilitylines (WCAG) 2.0</em></a> are a set of guidelines maintained by the <a href="http://www.w3.org" rel="external"><em>World Wide Web Consortium (W3C)</em></a> for making <a href="http://www.w3.org/TR/WCAG20/#contentdef" rel="external">content</a> more accessible to people with disabilities</p>
		<p>Web content is implemented through <a href="http://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=23601&amp;section=text#technology" rel="external">web content technologies</a> and accessed using <a href="http://www.w3.org/TR/WCAG20/#useragentdef" rel="external">user agents</a> (with or without assistive technologies). </p>
	</div>
	<div class="col-md-6">
		<div class="alert alert-info">
			<h3 class="mrgn-tp-0 h4">Examples</h3>
			<p>HTML is a type of <strong>web content technology</strong>.</p>
			<p>Web browsers are a type of <strong>user agent</strong>.</p>
			<p>Screen readers are a type of <strong>assistive technology</strong>.</p>
		</div>
	</div>
</div>
<h2 id="cfrm" class="page-header">Conformance requirements</h2>
<p>To ensure content is accessible to the widest possible audience, Government of Canada web pages must meet all five <a href="http://www.w3.org/TR/WCAG20/#conformance-reqs" rel="external">WCAG 2.0 conformance requirements</a> under the <em><a href="http://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=23601&amp;section=text#sec6.1" rel="external">Standard on Web Accessibility</a></em>. Web pages satisfy conformance requirements by using the <a href="http://wet-boew.github.io/wet-boew/demos/wamethod/wamethod-AA-en.html">thirty-eight (38) success criteria</a> listed at the A and AA levels of WCAG 2.0.</p>
<div class="row">
	<div class="col-md-6">
		<h3>Applicable success criteria</h3>
		<p>Success criteria are general statements, independent of technology, that need to be satisfied for content to claim conformance to WCAG 2.0.</p>
		<p>Depending on the type of content on a web page, individual success criterion may apply to all, some, or none of the content.</p>
		<div class="alert alert-warning">
			<p>For assistance determining what content is applicable to a success criterion, consult the <a href="applicability-en.html">WCAG 2.0 Success Criteria Applicability</a>.</p>
		</div>
	</div>
	<div class="col-md-6">
		<div class="alert alert-info">
			<h4>Examples</h4>
			<p><a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-captions.html" rel="external">Success Criterion 1.2.2: Captions (Prerecorded)</a> applies to captioning of video (with audio) and applies <strong>only</strong> to video (with audio) elements on a web page.</p>
			<p><a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-scale.html" rel="external">Success Criterion 1.4.4: Resize Text</a> applies to the ability to resize text on a web page and applies to all text on a web page.</p>
		</div>
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		<h3>Satisfying success criteria</h3>
		<p>Success criteria are satisfied by:</p>
		<ul>
			<li>
				<p>Avoiding all common failures; and</p>
			</li>
			<li>
				<p>Applying applicable sufficient techniques specific to the technologies used on the web page.</p>
			</li>
		</ul>
		<p>The step by step process to satisfy a success criterion follows:</p>
		<ol>
			<li>
				<p>For each <a href="http://wet-boew.github.io/wet-boew/demos/wamethod/wamethod-AA-en.html" rel="external">success criterion</a>, identify the <a href="applicability-en.html">applicable items of content</a> on the web page.</p>
			</li>
			<li>
				<p>For each occurrence of an applicable item of content:</p>
				<ol>
					<li>
						<p>Identify the <strong>web content technology</strong> used to implement the item.</p>
					</li>
					<li>
						<p>If present in the success criterion's list of sufficient techniques, identify the <strong>applicable situation</strong>.</p>
					</li>
					<li>
						<p>Ensure at least one<strong> sufficient technique</strong> from the success criterion (specific to the situation and web content technology used) is being satisfied. <em>General sufficient techniques</em> can be used by all web content technologies.</p>
					</li>
					<li>
						<p>Ensure the item avoids all <strong>common failures</strong>.</p>
					</li>
				</ol>
			</li>
		</ol>
	</div>
	<div class="col-md-6">
		<div class="alert alert-info">
			<h4>Examples</h4>
			<p><strong>Scenario:</strong> A HTML web page contains only headings and paragraphs. <a href="headings-en.html">Headings</a> are short text phrases which identify the section of content that immediately follows it.</p>
			<ol>
				<li>
					<p>For <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html" rel="external">Success Criterion 1.3.1 Info and Relationships</a>, any content conveying the meaning of a "heading" is applicable.</p>
				</li>
				<li>
					<p>For each "heading":</p>
					<ol>
						<li>
							<p><strong>HTML</strong> is the web content technology used to implement the item.</p>
						</li>
						<li>
							<p><strong>Situation A</strong> applies as HTML provides semantic structure to make information and relationships conveyed through presentation programmatically determinable.</p>
						</li>
						<li>
							<p><strong>Technique <a href="http://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H42" rel="external">H42</a></strong>, which is an HTML technique under Situation A, is satisfied by marking up the "heading" with <code>&lt;h1&gt;</code>, <code>&lt;h2&gt;</code>, etc.</p>
						</li>
						<li>
							<p><strong>Failures <a href="http://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/F2" rel="external">F2</a> and <a href="http://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/F43" rel="external">F43</a></strong> are avoided by ensuring all items that look like "headings" and only those items that are actually "headings" are marked up using Technique <a href="http://www.w3.org/TR/2012/NOTE-WCAG20-TECHS-20120103/H42" rel="external">H42</a>.</p>
						</li>
					</ol>
				</li>
			</ol>
		</div>
	</div>
</div>
<div class="row">
	<div class="col-md-6">
		<h3>When a success criterion cannot be satisfied</h3>
		<p>When an item of content cannot satisfy all applicable success criteria using a desired web content technology, an alternate version of the item in another web content technology that does satisfy all applicable success criteria must be provided.</p>
		<p>The original version does not need to be removed as long as it does not interfere with a user's ability to easily locate and access the alternate version and use the web page. The original version must also not present any additional information and/or functionality which is not found in the alternate version.</p>
		<div class="alert alert-danger">
			<p><strong>Note:</strong> An item of content that does not satisfy all applicable success criteria will not be fully supported by assistive technologies and accessibility features in user agents such as web browsers. This means that it is not possible for a user to access it in an <a href="http://www.w3.org/TR/WCAG20/#accessibility-supporteddef" rel="external">accessibility-supported</a> way.</p>
		</div>
	</div>
	<div class="col-md-6">
		<div class="alert alert-info">
			<h4>Examples</h4>
			<p><strong>Scenario:</strong> A Java Applet</p>
			<p>No success criterion can be satisfied because there are no sufficient techniques defined for Java Applet technology.</p>
			<p><strong>Solution:</strong> The applet's content would need to be provided in an alternate version. If the applet interferes with the usage of the web page, such as <a href="http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-trapping.html" rel="external">trapping keyboard functionality</a>, it must be removed.</p>
		</div>
	</div>
</div>
<h2 id="links" class="page-header">Related links</h2>
<ul class="list-unstyled">
	<li>Web Accessibility
		<ul>
			<li><a href="http://www.w3.org/WAI/" rel="external">W3C Web Accessibility Initiative (WAI)</a></li>
			<li><a href="http://www.w3.org/WAI/mobile/" rel="external">W3C Web Content Accessibility and Mobile Web</a></li>
			<li><a href="http://www.w3.org/WAI/intro/people-use-web/diversity" rel="external">Diversity of Web Users - How People with Disabilities Use the Web</a></li>
			<li><a href="http://webaim.org/" rel="external">Web Accessibility In Mind (WebAIM)</a></li>
			<li><a href="http://webaim.org/intro/" rel="external">WebAIM Video: Experiences of Students with Disabilities</a></li>
		</ul>
	</li>
	<li>Web Content Accessibilityline (WCAG) 2.0
		<ul>
			<li><a href="http://www.w3.org/TR/WCAG20/" rel="external">Overview</a></li>
			<li><a href="http://www.w3.org/WAI/WCAG20/quickref/" rel="external">Quick Reference</a></li>
			<li><a href="http://www.w3.org/TR/WCAG20-TECHS/intro.html" rel="external">Sufficient Techniques</a></li>
			<li><a href="http://www.w3.org/WAI/WCAG20/from10/comparison/" rel="external">Comparison of WCAG 1.0 to 2.0</a></li>
		</ul>
	</li>
	<li>Tools and Utilities
		<ul>
			<li><a href="http://www.paciellogroup.com/resources/wat-ie-about.html" rel="external">Internet Explorer Web Accessibility Toolbar</a></li>
			<li><a href="http://wave.webaim.org/" rel="external">Firefox Wave Toolbar Extension</a></li>
			<li><a href="https://addons.mozilla.org/en-US/firefox/addon/web-developer/" rel="external">Firefox Web Developer Toolbar Extension</a></li>
			<li><a href="https://addons.mozilla.org/en-us/firefox/addon/wcag-contrast-checker/" rel="external">Firefox Color Checker Extension</a></li>
			<li><a href="http://www.paciellogroup.com/resources/contrast-analyser.html" rel="external">Color Contrast Analyzer</a></li>
		</ul>
	</li>
	<li>Technologies
		<ul>
			<li><a href="http://www.w3.org/WAI/intro/aria" rel="external">Accessible Rich Internet Applications (WAI-ARIA)</a></li>
			<li><a href="http://www.w3.org/TR/html5/" rel="external">HTML5</a></li>
		</ul>
	</li>
	<li>Legislation and Policies
		<ul>
			<li><a href="http://laws.justice.gc.ca/eng/charter/page-1.html#anchorbo-ga:l_I-gb:s_15" rel="external">Canadian Charter of Rights and Freedoms</a></li>
			<li><a href="http://laws-lois.justice.gc.ca/eng/acts/H-6/page-1.html#h-3" rel="external">Canadian Human Rights Act</a></li>
			<li><a href="http://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=12541&amp;section=text#cha7" rel="external">Policy on the Duty to Accommodate</a></li>
		</ul>
	</li>
	<li>Demos
		<ul>
			<li><a href="http://www.w3.org/WAI/demos/bad/draft/2009/after/home/" rel="external">Citylights: Before and After demonstration</a></li>
		</ul>
	</li>
</ul>
{% endraw %}
{:/}
