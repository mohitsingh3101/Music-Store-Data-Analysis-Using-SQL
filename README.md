# 🎵 Music Store Data Analysis (SQL Project)

## 📁 Project Overview
This project is a *SQL-based data analysis* of an online music store. The analysis is performed using a relational database : MySQL. The database contains tables such as Customer, Invoice, Track, Artist, Album, Genre, and others that simulate a digital music store environment.

The project leverages *SQL queries* to derive business insights from the store's historical sales, customer behavior, music preferences, and employee data. 

You can explore:
- Who are the top customers?
- Which cities and countries generate the most revenue?
- What are the top-performing genres or artists?
- Which tracks are the longest or most purchased?

## 🧰 Tools Used
- *MySQL*: To import and query data using structured SQL commands.
- *CSV Files (11 total)*: Representing individual tables like Artist, Album, Customer, etc., used to populate the database.

## 📊 Business Objective
The primary objective of this project is to *analyze customer trends, musical preferences, and purchase behaviors* using SQL queries to answer specific business questions.
The project is divided into *three sets of questions* – Easy, Moderate, and Advanced – to provide step-by-step learning and analysis depth.

## 🧱 Database Schema
The dataset is relational and consists of the following key tables:

- *Artist*: ArtistId, Name  
- *Album*: AlbumId, Title, ArtistId  
- *Track*: TrackId, Name, AlbumId, MediaTypeId, GenreId, Composer, Milliseconds, Bytes, UnitPrice  
- *Genre*: GenreId, Name  
- *MediaType*: MediaTypeId, Name  
- *Customer*: CustomerId, FirstName, LastName, Country, Email, SupportRepId, etc.  
- *Employee*: EmployeeId, FirstName, LastName, Title, ReportsTo, etc.  
- *Invoice*: InvoiceId, CustomerId, InvoiceDate, Billing details, Total  
- *InvoiceLine*: InvoiceLineId, InvoiceId, TrackId, UnitPrice, Quantity  
- *Playlist / PlaylistTrack*: PlaylistId, TrackId

## 📂 Dataset
The analysis is based on *11 CSV files*, each representing one table from the schema above. These CSVs were imported into a MySQL database to run queries and extract insights.

---

📝 This project uses SQL concepts like:
- Joins (INNER, LEFT)
- Aggregations (SUM, COUNT, AVG)
- Filtering and sorting
- Subqueries and CTEs
- GROUP BY and HAVING clauses
- String functions and date functions

---

*Made by [Mohit Singh]*
