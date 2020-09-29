# Data importation

## Data table    
Datatables allow us to create data tables with features such as paging, instant search, export, and multi-column sorting.
DataTables comes with an extensive API that is used to manipulate or obtain information about the DataTables on a page.
In Python is widely used for fast aggregation of large datasets, low latency add/update/remove of columns, quicker ordered joins, and a fast file reader. Here you need to instal your modul:        

```import datatable as dt```   


![DataTable](https://miro.medium.com/max/1342/1*hgMH-aKTyU7UF43rf6n_Zg.png)

## Data Types
In computer science and computer programming, a data type or simply type is an attribute of data which tells the compiler or interpreter how the programmer intends to use the data. Some examples are categorical, numeric, boolean, dates and strings.

![Data Type](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcR1u8nGVBpW4sup-PeL-Slzs8lIiKK490qfMQ&usqp=CAU)

### Categorical
Represent characteristics such as a person’s gender, marital status, hometown, or the types of movies they like. Categorical data can take on numerical values for example  *1* indicating a person is male or *2* indicating female, however these numbers don’t have a mathematical meaning. Another examples is the typical YES/ NOT. In Pytho we can use the Categorical data with Pandas. 

![Categorical](https://o.quizlet.com/8UUywzzaMhY2ZGHrWE7VkA_b.png)

### Numeric 
Numeric data types are numbers stored in database columns. These data types are typically grouped by:

* Exact numeric types, values where the precision and scale need to be preserved. The  exact numeric types are INTEGER, BIGINT, DECIMAL, NUMERIC, NUMBER, and MONEY.
* Approximate numeric types, values where the precision needs to be preserved and the scale can be floating. The approximate numeric types are DOUBLE PRECISION, FLOAT, and REAL.

![Numerical](https://images.slideplayer.com/24/7512971/slides/slide_4.jpg)

### Booleans
the Boolean data type is a data type that has one of two possible values (usually denoted true and false) which is intended to represent the two truth values of logic and Boolean algebra. The Boolean data type is primarily associated with conditional statements, which allow different actions by changing control flow depending on whether a programmer-specified Boolean condition evaluates to true or false.

![Boolean](https://blog.digilentinc.com/wp-content/uploads/2014/12/boolean-true-false.png)

### Dates 
The Date data type stores the calendar date. DATE data types require four bytes. A calendar date is stored internally as an integer value equal to the number of days since December 31, 1899. The Date values are stored as integers, we can use them in arithmetic expressions. On another hand, The time data type consists of a time in hour, minutes, seconds, optional fractions of a second, and optional time zone.

![Date](https://aspnet.4guysfromrolla.com/images/dateDataTypes2.gif)

### Strings
A string is a data type used in programming, such as an integer and floating point unit, but is used to represent text rather than numbers. It is comprised of a set of characters that can also contain spaces and numbers. For example, the word "hamburger" and the phrase "I ate 3 hamburgers" are both strings.

![String](https://study.com/cimages/multimages/16/java_string_object.png)

## Common data formats

### Csv
CSV or comma separated values files are used to store tabular data in plain text format. Most often the fields in this data are separated by commas but other delimiters can be used such as |. TSV (tab separated values) files are similar but breaks are delimited by tabs. Both formats are widely supported and are often used to exchange data across multiple different computers and systems that support the format.

### Json
Json or javascript object notation one of the standart formats for sending data by HTTP request between web browsers and other applications. It is a much more free-fform data format than a tabular text form like CSV.

### Xml
Extensible Markup Language or XML is a markup language that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable. The design goals of XML emphasize simplicity, generality, and usability across the Internet. Although the design of XML focuses on documents, the language is widely used for the representation of arbitrary data structures such as those used in web services.
XML is generally more useful to developers and software systems.

### Xls
To maintain formatting data we will want to save in a proprietary format like XLS (Microsoft Office Excel), ODS (Open Office spreadsheets) or numbers (Apple Mac), depending on the software we use. 

## API VS URL

### API
Application Programming Interfaces. It is a set of definitions and protocols that is used to develop and integrate application software, allowing communication between two software applications through a set of rules. API is like a formal specification that establishes how a module of a software communicates or interacts with another to fulfill one or many functions. All depending on the applications that are going to use them, and the permissions that the API owner gives to third-party developers.

### URL
Universal Resource Locator. It is the specific address that is assigned to each one of the resources available on the network so that they can be located or identified. Thus, there is a URL for each of the resources (pages, sites, documents, files, folders) in internet.

### Difference
The key difference between an ordinary URL and a URL that's part of a web API is that an ordinary URL sends back something pretty designed to look good in your browser, whereas a web API URL sends back something ugly designed to be useful to a computer.

## Secure data transfer protocols

### HTTP (Hypertext Transfer Protocol)
HTTP file transfer is a widely used protocol for business file transfers. It's easy to implement, especially for person-to-server and person-to-person file transfers (read Exploring Use Cases for Managed File Transfer for reference).

### FTP (File Transfer Protocol)
FTP is built for both single file and bulk file transfers. It's been around for quite some time, so you likely won't have problems with interoperability. Meaning, there'll always be a good chance your trading partner will be able to exchange information through it. You won't have trouble finding a client application for your end users either. 

### FTPS (FTP over SSL)
The good news is that both FTP and HTTP now have secure versions. FTP has FTPS, while HTTP has HTTPS. Both are protected through SSL. If you use FTPS, you retain the benefits of FTP but gain the security features that come with SSL, including data-in-motion encryption as well as server and client authentication. Because FTPS is based on FTP, you'll still be subjected to the same firewall issues that come with FTP.

### HTTPS (HTTP over SSL)
As mentioned earlier, HTTPS is the secure version of HTTP. If you don't like having to install client applications for your end users and most of your end users are non-technical folks, this might be the perfect choice. It's secure and very user-friendly compared to FTP/S.

## Describe the procedures for data importing.

### Importing TXT
```
file = open("sample.txt")
data = file.read()
print(data)
file.close()
```

### Importing CSV
```
file = open("sample.csv")
data = file.read()
print(data)
file.close()
```
