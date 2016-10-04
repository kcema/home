#KcEMA Website

## adding content

### adding blog posts

checkout development

write content. Content is done in [Markdown](https://daringfireball.net/projects/markdown/syntax)

save new post in _posts with name in following format: 

{YEAR}-{MONTH}-{DAY}-short-title.markdown

Include the headers. YAML headers live between ---

Ex:

---
layout: singleblog
category: Video
title: Get to know ChucK and KcEMA President
description: Interview and Demo
tag: video
author: John Chittum
---

Required:

* layout:singleblog
* category: {ANYTHING}
* title: {ANYTHING}
* description: {ANYTHING}
* tag: {ANYTHING}
* author: {YOUR NAME}


# Landing Page Jekyll theme

Jekyll theme based on [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## How to use
 - Place a image in `/img/services/`
 - Create posts to display your services. Use the follow as an example:

```txt
---
layout: default
img: ipad.png
category: Services
title: The service title
---
The description of this service
```

## Demo
View this jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

For more Jekyll details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.

## License
The contents of this repository are licensed under the [Apache
2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## Version
1.0.1
