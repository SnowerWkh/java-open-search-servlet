# Introduction #

OpenSearch is a collection of technologies that allow to publish search results
in a format suitable for syndication.

It is a way for search engines to publish their search results in a standard and accessible format - taken from wikipedia

for example: you have a site where you made custom search engine. all of your contents can be searched using your managed search engine. so you let your user browse your site and let them hit your content by searching through your web based search form. but i belief you have noticed how google and other search engines are working around.

if you lucky guy like me of using firefox kinda browser you perhaps get a better searching experience. because you don't need to browse even google home page too, all your search are goes from the right most corner search text box.

what if you could add your search engine their ?, obviously that would give you a better fortune to get more hits from your visitors. that’s how this open search standard works.

it lets you add your searching URL syntax in a simple xml format. This open standard is meaning full to all open search supported browsers (firefox, ie 7…).

so whenever visitor browse your site they get a hints about your search engine, whether they want to add it on his beloved browser or not.. that’s how they can add your search engine without knowing everything.

this project is an implementation of supporting open search format. this project is intended to assist you to generate the xml file on the fly, the all you have to do is just map the servlet and put your configuration properties file in your class path.

and play !!!

## installation ##
[**binary installation**]
  * ensure "_open-search-1.0.jar_" file is on right place.
WEB-INF\lib\open-search-1.0.jar

  * we have dependency with log4j library. so ensure _log4j_ jar is on your classpath.
WEB-INF\lib\log4j-1.2.9.jar

[**source installation**]
  * download source files from subversion.
  * ensure you have maven installed
  * on your project directory execute the following command -
`mvn install -Dtest=false`
  * you will find your built files under the following location -
    1. _open-search-webapp\target\open-search-webapp.war_
    1. _open-search\target\open-search-1.0.jar_
  * we have only dependency on _log4j_

good luck