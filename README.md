# Exercise

The base of this project is https://github.com/spring-guides/gs-uploading-files.

From there the following endpoints were used: <br>
**/** - with both GET and POST fetching the current files and uploading a new <br>
**/files/filename** - a GET method to fetch the content of the file with the given filename

Newly implemented endpoints: <br>

**/uploadFile** - a POST method to upload a multipart file <br>
**/files** - a GET method to obtain the colection of documents currently in the system

Total time: <1h <br>
45 min coding and searching <br>
10 min describing and uploading to the repository <br>

Aditional things that may be considered/implemented if the time was more:
  - a monitoring system
  - a log system
  - dockerizing the application
  - saving the files in S3
  - saving the files and/or some metadata in database
  - saving the files with a unique name so that when a file with the same name is uploaded it would not replace it (md5 of the file name + timestamp + file extension)
