# data512-final

### Goal
The goal of this assignment is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1 2008 through August 30 2020. For this assignment, I combine data about Wikipedia page traffic from two different Wikimedia REST API endpoints into a single dataset, perform some simple data processing steps on the data, and then analyze that data.

### Resources and Documentation
License of the source data: https://www.mediawiki.org/wiki/RESTBase
Wikimedia REST API: https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions
Legacy Pagecounts API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

### Dataset
The final dataset used for the analysis is named en-wikipedia_traffic_200712-202008.csv. This dataset has 8 variables with the corresponding data types:
year: string
month: string
pagecount_all_views: number of views
pagecount_desktop_views: number of views
pagecount_mobile_views: number of views
pageview_all_views: number of views
pageview_desktop_views: number of views
pageview_mobile_views: number of views

### Other Considerations
For this analysis, data from the Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.

@article{shu2018fakenewsnet,
  title={FakeNewsNet: A Data Repository with News Content, Social Context and Dynamic Information for Studying Fake News on Social Media},
  author={Shu, Kai and  Mahudeswaran, Deepak and Wang, Suhang and Lee, Dongwon and Liu, Huan},
  journal={arXiv preprint arXiv:1809.01286},
  year={2018}
}
@article{shu2017fake,
  title={Fake News Detection on Social Media: A Data Mining Perspective},
  author={Shu, Kai and Sliva, Amy and Wang, Suhang and Tang, Jiliang and Liu, Huan},
  journal={ACM SIGKDD Explorations Newsletter},
  volume={19},
  number={1},
  pages={22--36},
  year={2017},
  publisher={ACM}
}
@article{shu2017exploiting,
  title={Exploiting Tri-Relationship for Fake News Detection},
  author={Shu, Kai and Wang, Suhang and Liu, Huan},
  journal={arXiv preprint arXiv:1712.07709},
  year={2017}
}
