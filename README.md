# Racoon
A movie collection web application used Spring MVC, MongoDB,Tomcat, Hibernate and AngularJS

Introduction
----
We want to build a movie collection web application that allows users to make their personal movie wishlists.
The system consists of four components:

1. Scrapy web crawler

   Our goal is to crawl 100,000 movies titles from IMDb in the past 30 years, from 1986 to 2016.

2. Restful API
    * getTopMovies: get top N apps from MongoDB
    * getRecomMovies: get M recommended apps from MongoDB
    * getMovieByID: get a single app from MongoDB, searching by movie name
    * APIs for create, update, get and delete a movie

3. Movie Recommender

4. Front-end implementation

Plan
----

### Todo List
- [x] Web crawler
- [ ] Set up Spring framework
- [ ] Implement a restful API
- [ ] Front-end implementation

### Time Schedule
We take _June, 2016_ as the __1st stage__ with the __primary__ goal of __prototyping__ our application following the development guild lines mentioned below. Here's the tentative timeline.

| Stage | Start  | End | Goals |
| ------------- | ------------- | ------------- | ------------- |
| 1 | 05/24/16  | 05/30/16  | Project Selection, Plan Discussion, and Proposal Draft Writing |
| 2 | 06/01/16  | 06/04/16  | Web Crawler With Scrapy |
| 3 | 06/05/16  | 06/11/16  | Building Java Web Application Using Hibernate With Spring |
| 4 | 06/12/16  | 06/18/16  | Implementation Restful APIs |
| 5 | 06/19/16  | 06/25/16  | Use Angular JS for the front end |
| 6 | 06/26/16  | 07/02/16  | User Manual Writing Video Presentation Making and Deploy on Heroku.|


## Team Members
| | | |
|:--:|:--:|:--:|
|![Likun Du](https://avatars1.githubusercontent.com/u/14044346?v=3&u=aeffbb5aa243d1f6cb6d2059a3eacd6c7b319743&s=140)|![icemintt](http://hdn.xnimg.cn/photos/hdn421/20131128/1910/p/m3w230h230q85lt_h_large_9QG5_def800002ef6113e.jpg)|![Simon Wang](http://hdn.xnimg.cn/photos/hdn421/20110808/0950/p/m3w306h230q85lt_h_large_GKwq_69100002f6f22f75.jpg)|
|[Likun Du](https://github.com/begdor)|[icemintt](https://github.com/icemintt)|[Simon Wang](https://github.com/AssassinW)|


## Resource
- [BitTiger Project: AppStore - Crawler](https://slack-files.com/T0GUEMKEZ-F0J4G9QTT-274d3bc97e)

## License
See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).

Owner
-----

@team: Racoon
