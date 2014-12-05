EbolaMapper
===========

**EbolaMapper** is a set of Web tools for visualizing outbreaks, including ebola. This includes Web components, mobile apps, and various secondaries like data validators, converters, and the like. In other words, it is **modern open-source anti-virus software**. 

Description
-----------
Here is a break out the phrase "modern open-source anti-virus software."

**Modern**: this means highly interacive Web based visualizations leveraging SVG, via D3.js. This works with any browser newer than IE8 (which is already fading fast in late 2014, at less than 10% of global usages, and Microsoft will stop supporting in 2016).

**Open-source**: The code is Apache 2.0 licensed (that is, do with it freely as you wish, commericially or otherwise). Data for the 2014 Ebola Outbreak in West Africa is also made available, as free open data ([PDDL licensed](http://opendatacommons.org/licenses/pddl/)). We have currated data and provide it via a RESTful Web service API based on the [Outbreak Time Series Specification](https://github.com/JohnTigue/EbolaMapper/wiki/Outbreak-Time-Series-Specification-Overview).

**Anti-virus software**: Ebola is a virus and this software project is anti-ebola (and pro-geeky humor).

Use it
------
**EbolaMapper** is white label-able, the components are Web page embeddable (iframe or otherwise) and can easy be styled via CSS to match the rest of a Web site. 

Since **EbolaMapper** is licensed under [the Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html) the code does not even need to attribute it to anyone. Please, take it and help the world. (We are, though, interested in showing off quality work in a gallery of deploys. So, drop us a line if you have a link we can add to the list.)

Fork (or simply download) this repository if you want to [deploy EbolaMapper](https://github.com/JohnTigue/EbolaMapper/wiki/Deployment-HOWTO). 
- Styling (CSS, etc.) is highly configurable and [well documented](https://github.com/JohnTigue/EbolaMapper/wiki/White-Label). 
- Any data source using the [Outbreak Time Series Specification] (https://github.com/JohnTigue/EbolaMapper/wiki/Outbreak-Time-Series-Specification-Overview) can be specified as an URL parameter.
The default settings are sane such that you can just grab a copy, throw the files up on a Web server, and quickly be up and running.

More info
---------
There is a lot of information is in [the EbolaMapper wiki](https://github.com/JohnTigue/EbolaMapper/wiki)

If you want to jump in and get involved:  
- [The To Do List](https://github.com/JohnTigue/EbolaMapper/wiki/To-Do-List) provides an overview of where things are at  
- [The Issue Tracker](https://github.com/JohnTigue/EbolaMapper/issues) is where to find the nitty-gritty

Blog posts about EbolaMapper can be found at:  
http://tigue.com/category/ebolamapper/

