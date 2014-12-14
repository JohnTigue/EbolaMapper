## EbolaMapper
EbolaMapper is Web technology for visualizing epidemiological outbreaks, including ebola. The project has Web components, mobile apps, and various secondaries such as data validators, converters, and the like. 

This project also defines the [Outbreak Time Series Specification](https://github.com/JohnTigue/EbolaMapper/wiki/Outbreak-Time-Series-Specification-Overview). Taken together the code and the data spec can be deployed atop existing Internet infrastructure to create a global outbreak monitoring network. The first iteration is rather simple but it demonstrates how it can be easily done and will hopefully be a seed which germinates into more sophisticated infrastructure. 

### Status
The schedule is to have EbolaMapper minimally viable by 2014-01-09. See, [the wiki](https://github.com/JohnTigue/EbolaMapper/wiki#status) for more details.

### Description
Jokingly, EbolaMapper can be described as **modern open-source anti-virus software**. Here is a break out that phrase.

**Modern**: this means highly interactive Web browser based visualizations leveraging SVG, via D3.js. EbolaMapper's dependencies works with any browser newer than IE8 (which is already fading fast in late 2014, at less than 10% of global usages, and Microsoft will stop supporting it in 2016). EbolaMapper also uses AnjularJS 1.3.x, another project which recognizes that IE8 is not worth the limitations it imposes on any forward looking effort. So, this is designed to be useful for the foreseeable future.

**Open-source**: The code is Apache 2.0 licensed (that is, do with it freely as you wish, commercially or otherwise). Data for the 2014 Ebola Outbreak in West Africa is also made available, as free open data ([PDDL licensed](http://opendatacommons.org/licenses/pddl/)). We have curated data and provide it via a RESTful Web service API based on the [Outbreak Time Series Specification](https://github.com/JohnTigue/EbolaMapper/wiki/Outbreak-Time-Series-Specification-Overview).

**Anti-virus software**: Ebola is a virus and this software project is anti-ebola (and pro-geeky humor).

### Uses
EbolaMapper is white label-able, or OEM-able, that is the components can be embedded with a Web page (iframe or otherwise) and can be easily styled via CSS to match the rest of a Web site look.

EbolaMapper is licensed under [the Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html) so deploys do not require any attribution. Please, take it and help the world. (We are, though, interested in showing off quality work in a gallery of deploys. So, drop us a line if you have a link we can add to the list.)

Fork (or simply download) this repository if you want to [deploy EbolaMapper](https://github.com/JohnTigue/EbolaMapper/wiki/Deployment-HOWTO). 
- Styling (CSS, etc.) is highly configurable and [well documented](https://github.com/JohnTigue/EbolaMapper/wiki/White-Label). 
- Any data source using the [Outbreak Time Series Specification] (https://github.com/JohnTigue/EbolaMapper/wiki/Outbreak-Time-Series-Specification-Overview) can be specified as an URL parameter.

The default settings are sane such that you can just grab a copy, throw the files up on a Web server, and quickly be up and running.

### More info
The best place to go for more information is the [EbolaMapper project's wiki](https://github.com/JohnTigue/EbolaMapper/wiki).

If you want to jump in and get involved:  
- [The To Do List](https://github.com/JohnTigue/EbolaMapper/wiki/To-Do-List) provides an overview of where things are at  
- [The Issue Tracker](https://github.com/JohnTigue/EbolaMapper/issues) is where to find the nitty-gritty

Blog posts about EbolaMapper can be found at:  
http://tigue.com/

