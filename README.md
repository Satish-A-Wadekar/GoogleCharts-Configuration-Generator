# GoogleCharts-Configuration-Generator
Hello friends today we are going to learn how to Generate the configuration of google chart and Implement it in your chart with some easy steps.

# Objectives & Scope of Google chart configuration generator.

Google has developed a very powerful library for charts, which has around 28 chart types. but to implement those charts in your application you need to go through their all configurations and understand each and every option which is very huge in numbers, now here's the problem, if you want to apply some options on your chart then you need to do this manually with some RND from scratch. 
Google has given so many configurations per chart which we cannot go through, in shorter period of time so it's quite tedious and time-consuming process to test all those options on your chart.

& because of time concern, developers try to find some other charts libraries, but frankly speaking if you ignore this time-consuming part of implementation then you can make your chart very customizable with so many features provided by google, but yes, we need to think at implementation time also. so how we can achieve this in shorter period of time & with some easy steps?

So, to skip this time consuming and tedious process and implement any chart with some easy steps purpose I have developed one module where we can achieve this with some clicks. 
with the help of my configuration generator module, we can apply any listen options and make our chart very customizable. 
it makes you to finalise your chart by play with available options and fine tuning, all you need to do is just keep applying option until you finalise your chart that's it.

# Key Features of my module is
1. just select chart type and then all existing options will be available for you to play with it.
2. Test any option on your selected chart on the fly

# How it works
in my module you just need to select chart of which you want to generate configuration JSON, once you select, all the existing google chart settings gets render on page with options where you can change their values and add custom values as per your choice. you can test your entered customs values on the fly, even you can try dummy JSON data on chart.

# How to use this Module
> Please find the video tutorial where i have explain the demonstration this module.
```
  https://www.youtube.com/watch?v=3j1HCgEvbDQ&feature=youtu.be
```
> Please find module URL here.
```
  http://googlecharts-configuration-generator.com/
```
We will go step by step on process of this module.

on top right there is a Help menu in which I have mentioned all the explanation of Google settings generator, though I am going to explain here step by step.

once you select Chart type from top right Menu, it will render all setting properties of selected chart type in Key-HTMLControl format where Key will be Google chart Settings property name and HTML control will any appropriate control which suits that Key e.g. Dropdown list, checkbox, colorpicker, textbox, textarea with default value of respective Key. you can change values also and put your own custom values.

beside every control it has its proper description also in Information icon, on mouse hover you will get the information in popup which has detailed description of respective property.

after every Information icon it has one more option which is Include checkbox, its says that if you want to try this option you just need to select this checkbox.

on Top of all these settings you can find Include All checkbox option which says that if you want to include all the settings properties into your chart, just select it.

on top Menu you will find 3 more options [Export, Apply, TryDummyData] (appears only on Chart type selection).

Export: to export all included properties in JSON format inside Modal Popup.
Apply: to apply all Included properties and draw new Chart with these properties. (by this you can fine tune all options.)
TryDummyData: if you want to apply any Dummy data on chart. just add in TryDummydata. chart will draw with this data.

once you done with all the customization and fine tuning, you just need to export your finalised configuration. it will give you google chart settings in JSON format. all you have to do is just copy these settings and pass it in your application under google chart implementation script or you can use my GoogleChartRendered plugin also if you want in your application that's it. Its done.
