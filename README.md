# UFOs

 ## Overview of Project
 
 An in-depth analysis of UFO sightings was performed on a JS script file with sighting information. We partnered with Dana, a data journalist, to build a webpage that will allow users to view the data (HTML) and a dynamic table that will present it. The website created allows users to filter UFO data per their search preferences: date, city, state, country, shape. In order to build this page, a table was created first from UFO data that was stored as a Javascript array. This table is then manipulated/filtered based on certain criteria. Lastly, by placing this table into an HTML file, users can view it with ease. Seven categories are returned in the table, two of which are not filter criterias: duration and comments pertaining to the sightings. Bootstrap was used to to customize page and equip the table with fully functional filters so users can interact with it. 

 
### Tools:

Javascript, HTML, Bootstrap 

### Dataset: 

data.js (UFO data)
 
 
 ## Results
 
 ###
 
Navigating this webpage consists of a very simple process of using the search criteria. The criteria users can filter by include date, city, state, country, and shape. The entire dataset is pre-filled on the homepage prior to even beginning to filter the data so we can glance at the format of each criteria prior to entering our desired input. For instance, in the date criteria, we should aim to enter our date in the format of: "1/10/2010". This example is visualized in graph "a". These limitations are derived from the dataset itself, therefore it is imperative that we filter the data to reflect the data exemplified on the page already. If we enter "01/10/2010," nothing would be produced in the table. 

To filter by state, we follow the format of the pre-filled data, which is entered in all lowercase letters. In graph "b" we exemplified data filtered by the state of Colorado, in lowercase. Four UFO sightings are returned, which provide the seven category details: date, shape, city, state, country, duration of the sighting, and any comments regarding the sighting. 


a. Example of data filtered by date: 1/13/2010.  
 
<img src="https://github.com/katmarcin/UFOs/blob/b5b85c9286ecb969fd3f0ab523e735e339beeaa9/UFOs/navigation.png" width="1200" height="570"/>

b. Example of data filtered by state: colorado.

<img src="https://github.com/katmarcin/UFOs/blob/b5b85c9286ecb969fd3f0ab523e735e339beeaa9/UFOs/navigation2.png" width="570" height="320"/>
 
 
 ## Summary
 
 
Altogether, this webpage provides clean data summary through the use of filters for UFO data. Webpages like this help data journalists like Dana to make reports using sources that are clean and consistent, thereby producing reports that are trustworthy and legitimate. Transparency is a key pillar of journalism. Journalists must be able to answer where they got their information from and whether their source is biased. Without legitimate sources, people may be wary to use data to draw conclusions. 

### Drawbacks and Recommendations

One drawback to this webpage design is redundant categories, such as country. Every sighting was documented in the US. This piece of data provides an unnecessary filter and table category which could have been deleted in order to make a cleaner table and webpage. If we modified our app.js file to filter out duration and omit duration as a table header in index.html, we would be able to provide a cleaner table. Another drawback to this page design pertains to the duration category in the table. This format from the dataset is inconsistent, so it presents itself as such in our webpage as well. For example, the format of some of the durations recorded vary such as "half an hour" and "5 mins." This is exemplified in graph "c". If users, wanted to filter by duration, if it were a filter category, they simply would not be able to because the duration does not follow a specific format. Some users might want to filter by the longest UFO sighting out of curiosity. However,for further development of the code, it may be better to remove the duration category altogether as it may be very time-consuming to modify each duration. In graph "c", there is a typo in row 8. "A few minutes" was recorded as "a few mintues". Another option would be to filter out only some durations, such as this typo. However, the variety in the format might be too time-consuming again. My recommendations overall for the further development of the code would be to remove the country column and filter category and duration column to produce a neater table and webpage.

<img src="https://github.com/katmarcin/UFOs/blob/13478f71fea37b4dce877a359d8caf70451e8e7c/UFOs/duration.png" width="140" height="320"/>
 

