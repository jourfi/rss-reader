# rss-reader


RSS Feature in content based website has been used by number of website owner around the world for get information of latest content information from online website.

RSS is a very simple broadcast feature which is used from introduce updated information to number of receivers.

RSS will automatically send changed content regularly to the user.

If you seen orange icon on many website, that means that website has provide content through RSS feed.

So, in this post we will make dynamic RSS feed by using PHP script from data has been fetch from Mysql database. In this post you can find out how to create your own custom RSS by using PHP script and Mysql. Before we will discuss which tag has been used to make RSS feed and what is use of that tag in RSS feed and lastly we will seen how to use PHP script for implementing dynamic RSS feed in PHP.

RSS feed must add following fields.

<?xml ?> - RSS feed must be start with this XML tag in which we have to define version of XML.

<rss> - Below XML tag we have start define RSS feed by using this tag, in which we can define version of RSS.

<channel> - In RSS feed first we have to create channel by using this tag.

<title> - RSS feed name has been define under this <title> tag.

<link> - RSS feed link has been define in <link> tag.

<description> - A short description of RSS feed must be set under this <description> tag.

<language> - We must have to define RSS feed language, which has been define under tag. For example, American English language RSS feed we have to write "en-us", here en is ISO-639 language code and us stand for ISO-3166 country codes.

All above tag has been in RSS feed header section, but all below tag will be used in body section of RSS feed which is under each item comes in the feed.

<item> - RSS feed item has been define by this tag.

<title> - RSS feed item title has been set under this tag.

<link> - Link of each item has been define under this <link> tag.

<description> - Under this tag we can define short description of each item, and description must contain at least 300 or more characters.

<pubDate> - Publication date of each item has been define under this <pubDate> tag and date must be ISO 8601 or RFC822 standard format.

<guid> - In RSS feed, we have to provide unique id for each item, which has been define under this <guid> tag.

<dc:creator>
- Name of the author has been define under this tag.
<enclosure> - Any media attachment like image or video link has been define under this tag, here we have also define size of attachment with it's mime type also.

