---
content_type: page
description: This section provides information on the software used for the course
  labs.
learning_resource_types: []
ocw_type: CourseSection
title: Study Materials
uid: 7e24c053-48d2-e845-aed2-1a2974ed5a2f
---

Access
------

### Tables

The only place that Access stores data is in the tables listed under the "Tables" tab of the database window. Queries, forms, reports and macros are simply ways in which you can manipulate data in the tables.

### Queries

Queries work off of tables. Essentially they are the main mechanism to "ask" questions about data in the database. Queries do not usually save data into a new table (there is a certain type of query called "make table" query if you want to make a copy of a table or create a new table based upon an existing one). Instead, a query is more like a shell that you design in order to view data in tables according to your prescription. For example, if you want to see all the Boston parcels in ZIP code 12345 you may use a query to see only these records as they sit in the "parcels" table.

### Query Design View:

> Field: Field(s) that you include for analysis and/or showing
> 
> Table: Source table of the field(s)
> 
> Total: Aggregate function like group by, maximum, etc.
> 
> Sort: Ascending or descending the records based on the Field
> 
> Show: If checked, field is displayed in query results
> 
> Criteria: Equivalent to WHERE-clause in the SQL or subcategory of criteria
> 
> OR: Selects records based on meeting one condition OR another condition
> 
> AND: Selects records based on meeting one condition AND another condition

### Forms and Reports

These tools work off of queries (which work off of tables). Although these are not discussed in detail during the course of 11.208, they are useful in presenting query results in a more polished format. For example, you can use reports to create labels or make a form to help with data entry.

### Statements

Statements are used in filters and queries to tell Access what to do. Access has an statement builder wizard that can be helpful if you understand the basic concept the statement you want to build. When you are in the design view of a query you can right click on the Criteria row and choose the "build" option. This opens up a statement builder window consisting of a work area (large blank box at the top of the window) and three columns of things to choose from to formulate statements. The first column is a series of existing forms, queries and other access objects that currently exist. The middle column is a list of items you have created in your database.

Helpful Language in a Query Design View
---------------------------------------

One helpful way to add criteria to your query is by looking for specific text in a table. By putting text in quotations ("text") you will force Access to look for text in that field that exactly matches the text in between the quotes. If you want to find text that has certain text within it you can use a like statement.

If you do not want to specify a specific piece of text you can use a "Like" statement. Like "cat" will find records with data in that field anywhere the word cat appears. For example, black cat, catastrophic, cataclysmic...

Printing
--------

### Printing During Lab Exercises

Instructions for printing from ArcView are included in Lab A. In some of the exercises, we ask you to print the results of queries. One way to do this is to:

1.  Shrink the window to a size that will fit on a page
2.  Arrange the window so that everything you want to show is visible
3.  Take a picture of your active window (press ALT+Print Screen) or a shot of the whole screen (press Print Screen). The image is saved in the clipboard.
4.  Paste the image into another application such as Microsoft Word.

If you are experiencing general printing difficulties, don't worry. Simply call over an instructor or lab monitor, show them your answer on the screen, and ask them to check you off for that question. While we want to be sure that you print successfully at some point, we want you to spend your time working on database and mapping skills, not on printing. Before you print, make sure that your name(s) is (are) on the page being printed (either as a header or as part of the text in the maps).

Hand in Your Lab Exercise at the End of the Session
---------------------------------------------------

Be sure that the names of everyone in your group are on the sheet. If you are behind at the end of a session, you can continue working over lunch, or during the evening. However, try not to fall too far behind. This course moves at a very fast pace. If you are having severe conceptual difficulties, see one of the instructors for personal attention during office hours. We are here to help!