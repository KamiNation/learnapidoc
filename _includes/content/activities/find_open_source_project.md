{: .activity_subtitle}
## <i class="fa fa-user-circle"></i> Activity: Find an open-source project with API doc needs
{% if page.permalink == "/workshop.html" %}{:.no_toc}{% endif %}

To find an open-source project with API doc needs:

1.  Go to the [GitHub Advanced Search](https://github.com/search/advanced).
2.  Under the **Issues Options** section, in the **With the labels** row, type `help wanted`. This is a standard tag that teams use to attract volunteers to their project (but some teams that need help might not use it).

    Scroll to the top and notice that `label: "help wanted"` automatically populates in the field.

3.  In this Advanced Search box at the top, add some additional keywords (such as `API documentation`) as well:

    <a class="noCrossRef" href="http://idratherbewriting.site/githubsearchopps"><img src="{{site.media}}/githubadvancedsearch2.png"/></a>

4.  Click **Search** and browse [the results](https://idratherbewriting.site/githubapidocs).

    In the results, you might want to look for a *REST API* project (rather than a [native-library API]({{site.rooturl}}nativelibraryapis_overview.html) such as a Java API). Developers don't often distinguish between the two with requests related to API documentation. If you see doc requests related to Java, C++, JavaScript, or some other programming-specific framework (with no identifiable endpoints), it's probably not a REST API. However, working on such a project could be equally fulfilling as a learning opportunity. It depends on what you're interested in.

    As you browse the results, are there any projects that look interesting or promising? If so, great. If not, adjust some of the keywords and keep looking.

5.  If searching GitHub doesn't yield any appropriate projects, try the following resources:

    * [Trending GitHub projects](https://github.com/trending)
    * [Crowdforge](https://crowdforge.io/)
    * [Up for Grabs](http://up-for-grabs.net/#/)
    * [Bus Factor](https://libraries.io/experiments/bus-factor)
    * [Code Triage](https://www.codetriage.com/)
    * [Changelog](https://changelog.com/)
    * [24-hour Pull Requests](https://24pullrequests.com)
    * [Programmableweb.com API directory](https://www.programmableweb.com/category/all/apis)

    {% include note.html content="You could spend a long time evaluating and deciding on open-source projects. For this activity, it's okay if you focus on a project that looks only mildly interesting. You don't need to commit to it. You can always change it later." %}

6.  After selecting a project, make notes on the following:

    *  Does the project involve a REST API?
    *  How does the project tag documentation-related issues? For example, does it use the "documentation" label?
    *  Identify the current state of the project's documentation. Are the docs robust, skimpy, nonexistent, extensive?
    *  How active is the project? (What is the frequency of commits?)
    *  How many contributors does the project have?

    {: .note}
    You don't have to actually reach out or interact with the team yet. You're just gathering information and analyzing documentation needs here.

{% if page.workshop_activities == true %}*For more information related to this activity, see [Find an open-source project]({{site.rooturl}}docapis_find_open_source_project.html).*{% endif %}
