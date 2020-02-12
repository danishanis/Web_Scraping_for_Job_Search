# Web_Scraping_Python_Project
*Web Scraping tool in Python to locate and extract Data Science job information from indeed.ca and visualize the most sought after job skills*

## Background

As per [www.infoworld.com](https://www.infoworld.com/article/3228245/the-80-20-data-science-dilemma.html), nearly 44ZB of data will be produced by the end of 2020, 90% of which will be unstructured in nature. Preparation of data for analysis takes up most of a Data Scientist's time (Source: Deloitte University Press) and this is particularly true for applications requiring extraction of data from websites, such as job search tools. As not all job search web-sites provide APIs, one of the most popular areas for web scrapping is online job search.

## Aim

Our aim was to find a website like [https://www.indeed.ca](https://www.indeed.ca) which allows web scraping and parse HTML pages with \data scientist" job titles to extract position title, employer, location, salary, etc. An important library used for this was the *BeautifulSoup* in Python for pulling data out of HTML and XML files. Our objective was to print a table with the scraping results and export those as a csv file. In addition to *position title*, *employer*, *location*, *salary*, etc., also added are columns corresponding to programming skills such as *Excel*, *Python*, *R*, *Java*, *C/C++*, *MATLAB*, *SAS*, *SQL*, *SPSS*, *Tableau*, *Hadoop*, *Spark* and assign 1 to the entry if that programming skill is mentioned in the job description and 0 otherwise.

**What is Web Scraping?**

Web scraping or web data extraction is an automatic software technique for extracting information from web-sites. Web scraping works based on identifying a structure of HTML tags in web-pages. This can be explained further with the schematic below:

![alt text](https://github.com/danishanis/Web_Scraping_for_Job_Search/blob/master/Images/image.png)
