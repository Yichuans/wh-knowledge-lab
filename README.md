# World Heritage Knowledge Lab

[The Knowledge Lab](https://yichuans.github.io/wh-knowledge-lab/) is an initiative by the [IUCN World Heritage Programme](https://www.iucn.org/theme/world-heritage/) to utilise the power of the web to effectively deliver knowledge on natural World Heritage sites. 

## About

We care deeply about the well-being of our rich natural heritage, which have increasingly become under accelerating threats. More rapid, accessible and easily digestible digital information, in particular through the provision of GIS and remote sensing, is urgently required to broaden our understanding as well as to inform better decision making. 

Digital products are increasingly becoming the *de facto* preferred means through which the public access information. Rather than producing papers and publications that are difficult to understand and time consuming read, we want to better connect with our users by improving the experience by adopting the idea of Digital By Default.

With little resources, we need to keep things simple, but focus on the most important part, one at a time. We try our best to make one thing work, and hopefully to make one thing work well without investing much time. We believe in the principle of open data, and an open source approach, so everything we do can be easily reproduced, scrutinised, and extended. We owe our thanks much to those who inspire us to head this way.

More specifically the Lab is:

- A central hub where all proof-of-concept and work-in-progress projects, small and big, are tracked for progress

- An entry point to access prototype applications and tools, analyses and findings

- A mechanism to gather feedbacks so we know whatever to do in the future should be of use to the user, you

# Prototypes

Here we present a collection of studies, analyses and tools that have been, or are being, developed using affordable technology, scientific research and data products to provide perspectives for natural World Heritage sites. We hope by sharing these work-in-progress as soon as possible via the web, so we would be able to accommodate what you think and to ensure no effort is spent on things that are not useful.

## 1. Land cover change

The first comprehensive land class mapping exercise for natural World Heritage with the dynamics of change. It is also the first time the web was used to deliver results. The result has potential in identifying threats manifested as change in land cover. 

- Result: GlobeLand30 data 2000-2010, for all natural sites up to 2015. 10 classes change matrix (sankey diagram visualisation) on the web portal to easily visualise trend of change.
- Issues: results not validated with unquantified quality across the world
- Tech stack: Web2py, Bootstrap, jQuery, D3js, D3js-Sankey plugin, leaflet. Data courtesy of National Geomatics Centre of China.

[Land cover change website](http://wh-app.yichuans.me/wh_app/landcover) | [Source on Github](https://github.com/Yichuans/World_Heritage_apps)

## 2. Forest Loss and Human Footprint

Accompanying the [paper](http://www.sciencedirect.com/science/article/pii/S0006320716310138), they hold site specific information that can be of use to practitioners on the ground, as well as a means through which to verify results and gain site level insight beyond information from a global data driven approach.

- Result: Derived work from [Hansen forest loss data](http://data.globalforestwatch.org/datasets/63f9425c45404c36a23495ed7bef1314), and [Human footprint data](http://wcshumanfootprint.org/) by the University Queensland and Wildlife Conservation Society; quantitative breakdowns and with maps, to track change over time.
- Issues: only forest loss but not deforestation; no distinction between primary forest and plantation; change may be a result natural process (for example habitat succession), and it is not without difficulty in interpreting the result with contextual information and on the ground knowledge.
- Tech stack: Pelican, Bootstrap, Disqus comments.

[Forest Loss](http://forest-loss.yichuans.me/output/) | [Source on Github](https://github.com/Yichuans/forest-loss)

[Human Footprint Change](http://human-footprint.yichuans.me/output/) | [Source on Github](https://github.com/Yichuans/human-footprint)

## 3. Climate change and species vulnerability

The first data analytics exercise involving version control, open, accessible, reproducible methods. A new way of analysing data, delivering results and communicating knowledge products, throughout its life cycle (from inception to deployment). A good example of the digital by default approach.

- Result: Derived work from [Foden 2012](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0065427). Entirely open, including data, method and results and reports, all of which are available online
- Issues: review process is complicated for those not familiar with a version control system such as Github.
- Tech stack: web2py, JSON service-based for future extendibility, D3js

[Climate change vulnerability](http://wh-app.yichuans.me/ccv) | [methodology](http://nbviewer.jupyter.org/github/Yichuans/climate-vulnerable-wh/blob/master/workspace.ipynb) and [report](http://nbviewer.jupyter.org/github/Yichuans/climate-vulnerable-wh/blob/master/report.ipynb) | [Source on Github](https://github.com/Yichuans/climate-vulnerable-wh)

## 4. Near real-time Landsat 8 imagery 

The first purely front end application based on esri web services. The result is dynamically updated whenever new landsat 8 images are acquired. This is an entirely redeveloped product that ditched the original idea that data will be archived onsite, thanks to availability of landsat data as web services.

- Result: Using time series data for WH with near-real time monitoring, in a more accessible and timely way.
- Issue: relies on external landsat services, currently for views only and very limited analytical function, for example dynamic band combination.
- Tech stack: esri web services and esri calcite framework

[Landsat 8 imagery for natural World Heritage](http://wh-app.yichuans.me/landsat) | [Source on Github](https://github.com/Yichuans/landsat)

## 5. World Heritage Boundary
The World Heritage boundary is intended to replace the aging KML format to enable data dissemination and visualisation. Off the shelf esri feature service and web app.

[World Heritage boundary](http://wcmc.io/3f3e)

## 6. Global spatial comparative analysis (prototype version)

[Comparative analysis](http://whca.yichuans.me/) | [Source on Github](https://github.com/Yichuans/comparative-analysis-online)

## 7. World Heritage information sheet / WCMC datasheet

[Information sheet](http://52.16.74.158/wh_app/default/wh_html_bs2/191) | Source on Github


## The Knowledge Lab itself

This page hosts the website of the World Heritage Knowledge Lab itself

The design is inspired on [Start Bootstrap](http://startbootstrap.com/), [Stylish Portfolio](http://startbootstrap.com/template-overviews/stylish-portfolio/)