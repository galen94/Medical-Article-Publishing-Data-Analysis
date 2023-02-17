# Medical-Article-Publishing-Data-Analysis

Designed and implemented a normalized, relational OLTP database in mySQL using data acquired by looping through
an inconsistent XML file node by node in R.

Transformed normalized schema into a star schema suitable for OLAP and implemented the star schema to perform
simple data mining. Used Amazon RDS to store the OLTP and OLAP databases that were created in RStudio.

![Schema](https://user-images.githubusercontent.com/90521087/219750049-2709cf42-381b-4526-bc9a-9c34bd43f0ad.JPG)


From our findings we can report that there are more author publications in the fall and more journal publications in the winter.

![AuthorPubs](https://user-images.githubusercontent.com/90521087/219749991-f9493269-2d98-46ff-af7b-d79395b67cb6.JPG)
![JournalPubs](https://user-images.githubusercontent.com/90521087/219750015-75b5c36c-eacd-4daf-b6f9-46eb2defab8f.JPG)
