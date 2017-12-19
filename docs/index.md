# Rest Assured - Telosys 3 Template

This template is used by [Telosys](http://www.telosys.org/) to generate a test Rest Assured which is a JUnit test specification. You can find this template [here](https://github.com/so-technology-watch/telosys-templates-restassured).

## Prerequisites

* Java version 7/8
* Maven Project


## Installation

Refer to [Telosys Online Documentation](https://sites.google.com/site/telosystools/getting-started) to download and use the template.


## Template Configuration

#### For starting users

After generating all the necessary files to REST Assured [(Part 6 - Generate the code of Telosys documentation)](https://sites.google.com/site/telosystools/getting-started/generate-the-code).


Rename the original `pom.xml` to `pom_back.xml` and then change the `pom_for_rest-assured.xml` to `pom.xml`. 

And then run in terminal :
```bash
~ mvn clean install
```

Or for eclipse users execut :

* Maven clean
* Maven install

This will install all the dependencies used by the templates.

#### For advanced users

You can manually add the dependancies used by the project into your original `pom.xml` file.

Refer to the [depencies part](#dependencies-used) of the documentation


## Configuration

In `src/test/resources/restAssured.properties` you configure the destination address of test your API : 

* baseURI
* port
* basePath


## Start test

After genereating and setting up your projet, you can run the test JUnit for all projet or just entity wanted.  


## Dependencies used
 
 <table>
  <tbody>
    <tr>
      <th align="center">Dependencies</th>
      <th align="center">Version</th>
    </tr>
    <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/junit/junit/4.12">junit</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-4.12-brightgreen.svg" />
      </td>
    </tr>
        <tr>
      <td>
      <a href="http://mvnrepository.com/artifact/io.rest-assured/rest-assured/3.0.3">rest-assured</a>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/version-3.0.3-brightgreen.svg" />
      </td>
    </tr>
  </tbody>
</table>
<br/>

