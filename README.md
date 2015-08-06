# roundhouse-sample
This is a sample project for using [RoundhousE](https://github.com/chucknorris/roundhouse) in .NET project, built by Visual Studio 2013 with .NET 4.5 and 3.5 (just for database versioning with RoundhousE).
It reflects to the [post](http://gurunh.com/2015/08/database-versioning-with-roundhouse/) on my blog.

# To run
- Create a database **MusicStore**
- Create a login with credential (*MusicStore* / *mypassword*) and map it to **MusicStore** database with *db_owner* role.
- Change your settings in file **DBDeploy_MSBuild.proj**, especially the *DBConnectionString*

# To use
An easiest way to use RoundhousE in your project is adding the **DbVersioning.MusicStore** to your solution as an existing project. And of course, change the settings in files **DBDeploy_MSBuild.proj** and **_BuildInfo.xml** to match your environment.
