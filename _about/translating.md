---
title: "DRAFT UPDATE: Translating WAI Documents"
nav_title: Translating
github:
  repository: w3c/wai-about-wai
  path: '_about/translating.md'
feedbackmail: wai@w3.org
footer: |
  <p><strong>Date:</strong> Updated @@ January 2018.</p>
  <p><strong>Editor:</strong> <a href="http://www.w3.org/People/shawn">Shawn Lawton Henry</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page provides guidance on translating WAI resources.<br>If you want a list of existing translations, see [All WAI Translations](@@).

{::nomarkdown}
{% include box.html type="end" %}
{:/}


{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}


Thank you for your interest in translating resources from the World Wide Web Consortium (W3C) Web Accessibility Initiative (WAI).

You are welcome to translate any WAI resource. For suggestions on which to translate first, see [Priorities for Translations below](#priorities).

**Scope:**
* The instructions cover web pages with a URI that begins with www.w3.org/WAI
* For web pages that begin with www.w3.org/TR/ there is a different process that is being updated in early 2019. Some information is in [TR Translations below](#tr).

## Translation Steps

**If you want to translate a WAI resource:**

1. Read [Important Translations Guidance below](#important).
2. Check that there is not already a translation completed or in-progress. _{@@link to list – hopefully W3C list; otherwise, maybe All WAI Translations & WCAG 2 Translations – but that doesn’t get in-progress…}_
3. Indicate your interest in translating the resource by _{@@GitHub issue for W3C system – or sending an e-mail to the [w3c-translators@w3.org mailing list](mailto:w3c-translators@w3.org) &/or public-wai-translations@w3.org …}_
   * WAI staff will send you an e-mail letting you know that the resource is ready to be translated.

**To translate a WAI resource:**

After you have completed the steps above and after you have received notification that the resource is ready to be translated, follow the steps below **_either_** in GitHub or via e-mail. _(Translations submitted via GitHub can usually be processed faster.)_

**_If you can use GitHub:_** {#git}

4. Go to the English version of the resource. Near the bottom, in the "Help improve this page" box, select the "Fork & Edit on GitHub" button.
5. Make a change and save the file:
   * Add the language code to the middle of the filename (near the top), for example, **index.zh.md**
   * In the Commit changes area near the bottom:
       * Select the option button for "Create a new branch for this commit and start a pull request." 
       * Change the branch name (from ''you-patch-1'') to ''[language code]-translation'' using the language codes from [IANA language code](https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry); for example:<br>**zh-translation**
   * Click the "Propose file change" button.
6. You can preview your translation from _{@@}_
7. When you are done with your translation, create a new pull request. Under "Assignees", put ''slhenry''. If you have suggestions for Reviews who use GitHub, you can select them under Reviewers. If they are not in GitHub, you can list their name and contact info in the comment area.
   * We will contact you if something is needed. Otherwise, you will get notification from GitHub when the translation is published.

**_If you are not comfortable with GitHub, use e-mail:_** {#nogit}

4. Go to the English version of the resource.
   * Near the bottom, in the "Help improve this page" box, select the "Fork & Edit on GitHub" button.
   * Select all the text from the "Edit file" area. (You can probably: click anywhere in the text area, select all (in Windows: Ctrl+A; Mac: cmd+A), copy (in Windows: Ctrl+C; Mac: cmd+C).
   * Paste it into a text file.
5. When you are done with your translation, e-mail it to [public-wai-translations@w3.org with subject: Completed Translation – {language code} – {resource title}](mailto:public-wai-translations@w3.org?subject=Completed%20Translation%20%E2%80%93%20%5Blanguage%20code%5D%20%E2%80%93%20%5Bresource%20title%5D)
   * We will contact you if something is needed. Otherwise, we will send you e-mail when the translation is published.

## Important Translations Guidance {#important}

* **Do not change or adapt or add to the meaning of the English version in your translation**. If you have suggestions for changes to the English version, submit them via GitHub or e-mail with the links in the "Help improve this page" box near the bottom of the page.
* Check if there is any translation guidance for the specific resource.
   1. Go to the English version of the resource. Near the bottom, in the "Help improve this page" box, select the "New GitHub Issue" button.
   2. Near the top, click the path after "w3c/", which usually starts with "wai-".
   3. Scroll down to the README.md section. Any guidance will be under a heading "Translation Notes".
* Check if there is any translation guidance for the specific language. _{@@link}_
* Make sure to translate image alts.
* Please leave the code, HTML, and markdown as is without changing it (other than at the top as noted after #).

By submitting a translation, you agree:
* To the redistribution terms of the [W3C Document License](https://www.w3.org/Consortium/Legal/2015/doc-license). Your translation may be republished by the W3C or other entities if it is done in compliance with the License terms.
* That the W3C may rescind your right to publish or distribute the derivative work if the W3C finds that it leads to confusion regarding the original document's status or integrity. ([Source](http://www.w3.org/Consortium/Legal/IPR-FAQ-20000620#translate).)

### Updating Resources

If the English version of a resource is updated, we will inform translators what has changed, and request that translators update their translation.

If the changes are only small changes, such as a new paragraph or a new short section, we might add the English to the translation while awaiting an update. If the changes are substantive, the translation will be removed until an updated version is provided.

### Additional Information

More information is available in W3C's <a href="http://www.w3.org/Consortium/Legal/IPR-FAQ-20000620">intellectual rights FAQ</a>, particularly under the questions starting with <a href="http://www.w3.org/Consortium/Legal/IPR-FAQ-20000620#translate">can I translate one of your specifications into another language?</a>

General information about [Translations at W3C]( http://www.w3.org/Consortium/Translation/) is being updated in 2019.

## WAI Translations Mailing List {#mailinglist}

* To subscribe, send e-mail to <a href="mailto:public-wai-translations-request@w3.org?subject=subscribe">public-wai-translations-request@w3.org with subject: &ldquo;subscribe&rdquo;</a>.
* To unsubscribe, send e-mail to <a href="mailto:public-wai-translations-request@w3.org?subject=unsubscribe">public-wai-translations-request@w3.org with subject: &ldquo;unsubscribe&rdquo;</a>.

You can also see the [WAI Translations List Archives ![External](//www.w3.org/Icons/tr.png)](http://lists.w3.org/Archives/Public/public-wai-translations/).

## Priorities for Translating WAI Resources {#priorities}

<p><strong>You are welcome to translate any current WAI resource that you think would be useful in your language.</strong> The lists below are only suggested priorities.</p>
<ol>
<li>High priority introductory resources</li>
<li>High priority WCAG resources</li>
<li>Main navigation overview pages</li>
<li>Secondary priority resources</li>
<li>Design and development resources</li>
<li>To be updated (might want to wait to translate)</li>
</ol>

<h3>High priority introductory resources</h3>
<ul>
<li><a href="https://www.w3.org/WAI/fundamentals/accessibility-intro/">Introduction to Web Accessibility</a></li>
<li><a href="https://www.w3.org/WAI/videos/standards-and-benefits/">Video Introduction to Web Accessibility and W3C Standards</a> (including  VTT file)</li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/">W3C Accessibility Standards Overview</a></li>
<li><a href="https://www.w3.org/WAI/fundamentals/accessibility-principles/">Accessibility Principles</a></li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/mobile/">Mobile Accessibility at W3C</a></li>
</ul>

<h3>High priority WCAG resources</h3>
<ul>
<li><a href="http://www.w3.org/TR/WCAG21/">Web Content Accessibility Guidelines (WCAG) 2.1</a> &mdash; the Web Standard / W3C Recommendation ([TR process](#tr))
<ul>
<li><a href="http://www.w3.org/WAI/WCAG20/translations">WCAG 2 Translations</a> lists existing translations</li>
<li>This document may be developed as an <a href="http://www.w3.org/2005/02/TranslationPolicy.html">Authorized W3C Translation</a></li>
<li>To get the latest update with errata included, use the <a href=" https://w3c.github.io/wcag/21/guidelines/">Editor's Draft</a></li>
</ul>
</li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/wcag/">WCAG Overview</a></strong> </li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/wcag/glance/">WCAG 2.1 at a Glance</a></li>
</ul>

<h3>Main navigation overview pages</h3>
<ul>
<li><a href="https://www.w3.org/WAI/fundamentals/accessibility-intro/">Introduction to Web Accessibility</a> <em>(repeat from above)</em></li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/">W3C Accessibility Standards Overview</a> <em>(repeat from above)</em></li>
<li><a href="https://www.w3.org/WAI/test-evaluate/">Evaluating Web Accessibility Overview</a></li>
<li><a href="https://www.w3.org/WAI/design-develop/">Design and Develop Overview</a></li>
<li><a href="https://www.w3.org/WAI/planning/">Planning and Policies Overview</a></li>
<li><a href="https://www.w3.org/WAI/teach-advocate/">Teach and Advocate Overview</a></li>
<li><a href="https://www.w3.org/WAI/">WAI home page</a> (see notes on which parts to translate)</li>
</ul>

<h3>Secondary priority resources</h3>
<ul>
<li><a href="https://www.w3.org/WAI/people-use-web/">How People with Disabilities Use the Web</a> &mdash; 4 pages</li>
<li>Other standards overviews:
<ul>
<li><a href="https://www.w3.org/WAI/fundamentals/components/">Essential Components of Web Accessibility</a></li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/aria/">WAI-ARIA Overview</a><em> (this page will be updated in the future; however, it could be many months before it is updated)</em></li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/uaag/">User Agent Accessibility Guidelines (UAAG) Overview</a></li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/uaag/">Authoring Tool Accessibility Guidelines (ATAG) Overview</a></li>
</ul>
</li>
<li> Advocating and teaching resources:
<ul>
<li><a href="https://www.w3.org/WAI/perspective-videos/">Web Accessibility Perspectives: Explore the Impact and Benefits for Everyone</a> &mdash; main page, 10 sub-pages including transcripts</li>
<li><a href="https://www.w3.org/WAI/business-case/">The Business Case for Digital Accessibility</a></li>
<li><a href="https://www.w3.org/WAI/teach-advocate/accessible-presentations/">How to Make Your Presentations Accessible to All</a></li>
<li><a href="https://www.w3.org/WAI/teach-advocate/contact-inaccessible-websites/">Contacting Organizations about Inaccessible Websites</a></li>
</ul>
</li>
<li><a href="https://www.w3.org/WAI/planning/interim-repairs/"></a>Planning and managing resources:
<ul>
<li><a href="https://www.w3.org/WAI/planning/interim-repairs/">Web Accessibility First Aid: Approaches for Interim Repairs</a></li>
<li><a href="https://www.w3.org/WAI/planning/involving-users/">Involving Users in Web Projects for Better, Easier Accessibility</a></li>
<li><a href="https://www.w3.org/WAI/test-evaluate/tools/selecting/">Selecting Web Accessibility Evaluation Tools </a></li>
</ul>
</li>
</ul>

<h3>Design and development resources</h3>
<ul>
<li><a href="https://www.w3.org/WAI/tips/developing/">Tips for Getting Started    Developing for Web Accessibility </a></li>
<li><a href="https://www.w3.org/WAI/tips/designing/">Tips for Getting Started Designing for Web Accessibility </a></li>
<li><a href="https://www.w3.org/WAI/tips/writing/">Tips for Getting Started    Writing for Web Accessibility </a></li>
<li><a href="https://www.w3.org/WAI/tutorials/">Web Accessibility Tutorials</a> &mdash; main page and many sub-pages</li>
<li><a href="https://www.w3.org/TR/wai-aria-practices-1.1/"><abbr title="Accessible Rich Internet Applications">WAI-ARIA</abbr> Authoring Practices 1.1</a> ([TR process](#tr))</li>
</ul>

<h3>To be updated <em>(might want to wait to translate)</em></h3>
<p>The following pages will be updated, and you might want to wait to translate them until after they are updated. To get announcements when they are updated, see <a href="https://www.w3.org/WAI/news/subscribe/">Get WAI News</a> and subscribe to the [WAI Translations maling list, per above](#mailinglist).</p>
<ul class="old">
<li><a href="https://www.w3.org/WAI/standards-guidelines/harmonization/"></a><a href="https://www.w3.org/WAI/about/">About W3C WAI </a>&mdash; minor update planned for 2019</li>
<li><a href="https://www.w3.org/WAI/about/participating/">Participating in WAI</a> (see notes on which parts to translate) &mdash; minor update planned for 2019</li>
<li><a href="https://www.w3.org/WAI/test-evaluate/preliminary/">Easy Checks - A First Review of Web Accessibility</a> &mdash; significant update planned for 2019</li>
<li><a href="https://www.w3.org/WAI/standards-guidelines/harmonization/">Why Standards Harmonization is Essential to Web Accessibility</a> (no date set for the update to be completed)</li>
</ul>

<h3>Others</h3>
<p><strong>There are many more WAI resources available for translation. The complete list of WAI resources is available in the <a href="http://www.w3.org/WAI/sitemap.html">WAI Site Map</a>.</strong></p>

## TR Translations & Authorized W3C Translations {#tr}

For web pages at URIs that begin with www.w3.org/TR/ there is a different process that is being updated in early 2019. Previous information is available in [W3C Translations](https://www.w3.org/Consortium/Translation/).

Most translations are informative and unofficial. In cases where standards translations are meant for official purposes, they may be developed as Authorized W3C Translations according to the **[Policy for Authorized W3C Translations]( http://www.w3.org/2005/02/TranslationPolicy.html)**. Generally only completed W3C Recommendations and Working Group Notes are candidates for Authorized W3C Translations, including the WAI guidelines. The authorized translations policy is designed to ensure transparency and community accountability in the development of authorized translations under the oversight of W3C.
