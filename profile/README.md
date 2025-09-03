## Liturgical App ✨📖

Liturgical App is a set of components that can be used to find information about the 
[liturgical calendar](https://en.wikipedia.org/wiki/Liturgical_year) of the
[Church of England](https://en.wikipedia.org/wiki/Church_of_England), including
[liturgical colours](https://en.wikipedia.org/wiki/Liturgical_colours), and
[saints' days](https://en.wikipedia.org/wiki/Calendar_of_saints_(Church_of_England)).

So far, we are working on the following components:

* [liturgical-calendar](https://github.com/liturgical-app/liturgical-calendar), a Python library to calculate the dates and colours
* [liturgical-api](https://github.com/liturgical-app/liturgical-api), a small API server to return data from the library
* [liturgical-app](https://github.com/liturgical-app/liturgical-app), a simple web app to display liturgical colours
* [charts](https://github.com/liturgical-app/charts), Helm charts to install these components on Kubernetes

In the future we hope to work on:

* a Wordpress plugin to display liturgical colours on Wordpress-based sites
* an Alexa skill so people can ask their Amazon Echo for liturgical information
* a Home Assistant integration to display liturgical colours on RGB lighting

### Background

Some churches use a special church calendar. Days and seasons within the year
may be either "fasts" (solemn times) or "feasts" (joyful times). The year is
structured around the greatest feast in the calendar, the festival of the
Resurrection of Jesus, known as Easter, and the second greatest feast, the
festival of the Nativity of Jesus, known as Christmas. Before Christmas and
Easter there are solemn fast seasons known as Advent and Lent respectively.
After Christmas comes the feast of Epiphany, and after Easter comes the feast
of Pentecost. These days have the adjacent seasons named after them.

The church's new year falls on Advent Sunday, which occurs around the start of
December. Then follows the four-week fast season of Advent, then comes the
Christmas season, which lasts twelve days; then comes Epiphany, then the
forty days of Lent. Then comes Easter, then the long season of Pentecost
(which some churches call Trinity, after the feast which falls soon after
Pentecost). Then the next year begins and we return to Advent again.

Along with all these, the church remembers the women and men who have made
a positive difference in church history by designating feast days for them,
usually on the anniversary of their death. For example, we remember St. Andrew
on the 30th day of November in the Western churches. Every Sunday is the feast
day of Jesus, and if it has no other name is numbered according to the
season in which it falls. So, for example, the third Sunday in Pentecost
season would be called Pentecost 3.

Seasons are traditionally assigned colours, which are used for clothing and
other materials. The major feasts are coloured white or gold. Fasts are
purple. Feasts for martyrs (people who died for their faith) are red.
Other days are green.

### People

We are two volunteers in the UK, working on this project for fun and in the hope it will be useful to someone. We will gladly accept offers of help, and new ideas. Please drop us an issue in one of the projects.

