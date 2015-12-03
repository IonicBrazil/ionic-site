---
layout: "v2_fluid/docs_base"
version: "nightly"
versionHref: "/docs/v2/nightly"
path: ""
category: api
id: "{{Checkbox | slugify}}"
title: "Checkbox"
header_sub_title: "Class in module "
doc: "Checkbox"
docType: "class"
---



<div class="improve-docs">
  <a href='http://github.com/driftyco/ionic2/tree/master/ionic/components/checkbox/checkbox.ts#L3'>
    View Source
  </a>
  &nbsp;
  <a href='http://github.com/driftyco/ionic2/edit/master/ionic/components/checkbox/checkbox.ts#L3'>
    Improve this doc
  </a>
</div>




<h1 class="api-title">

  Checkbox



</h1>





<p>The checkbox is no different than the HTML checkbox input, except it&#39;s styled differently.</p>
<p>See the <a href="https://angular.io/docs/js/latest/api/core/Form-interface.html">Angular 2 Docs</a> for more info on forms and input.</p>





<pre><code class="lang-html">&lt;ion-checkbox checked=&quot;true&quot; value=&quot;isChecked&quot; ng-control=&quot;htmlCtrl&quot;&gt;
  HTML5
&lt;/ion-checkbox&gt;
</code></pre>




<h1 class="class export">Checkbox <span class="type">class</span></h1>
<p class="module">exported from <a href='undefined'>ionic/ionic</a><br/>
defined in <a href="https://github.com/driftyco/ionic2/tree/master/ionic/components/checkbox/checkbox.ts#L4-L123">ionic/components/checkbox/checkbox.ts (line 4)</a>
</p>
<h2>Component</h2>
  <span>selector: ion-checkbox</span>

  <span>inputs: value, checked, disabled, id</span>


<h2>Members</h2>

<div id="onInit"></div>
<h3>
  <code>onInit()</code>

</h3>












<div id="toggle"></div>
<h3>
  <code>toggle()</code>

</h3>

Toggle the checked state of the checkbox. Calls onChange to pass the updated checked state to the model (Control).










  <h2>Attributes:</h2>
  <table class="table" style="margin:0;">
    <thead>
      <tr>
        <th>Attribute</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      
      <tr>
        <td>
          checked
        </td>
        <td>
          whether or not the checkbox is checked (defaults to false)
        </td>
      </tr>
      
      <tr>
        <td>
          value
        </td>
        <td>
          the value of the checkbox component

        </td>
      </tr>
      
    </tbody>
  </table>



