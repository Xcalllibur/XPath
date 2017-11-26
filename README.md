XPath Visualiser

This tool allows you to develop and test XPath 1.0 expressions. You can visualise the results of the XPath expression on a piece of text, which can be any form of markup, including HTML, SOAP and XML.

Why is this tool different from other XPath visualiser tools?

The big advantage of this tool is that it is very forgiving on the structure of the markup that is being used. You can even use incomplete markup fragments without matching elements! The problem with many other XPath visualisation tools is that they require the markup to be 100% valid syntax. This is because behind the scenes they use the .NET XML library which has very strict requirements about the XML that it will process. The problem is, that many HTML and other markup sources are less than perfect, meaning they cannot be used in such tools.

Behind the scenes, this tool uses the wonderful HTML Agility Pack, which is very forgiving when processing the markup and allows virtually any source to be used and tested against your XPath expressions. Contrary to the name, this tool can process all markup sources, not just HTML.

This interface of this tool is very clean and simple, providing you with quick and simple testing of your XPath expressions. Currently there is no XPath builder included, but this may change in the future. The tool itself is the first non MVVM application i have developed in WPF. My goal was to knock this tool up very quickly as it was something i needed to complete another project. I thought it might be useful to others so let me know if you find it useful.
