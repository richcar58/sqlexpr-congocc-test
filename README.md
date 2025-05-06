# SqlExprParserTester

This project tests SqlExprParser code contained in that library's JAR file.  See [sqlexpr-congocc](https://github.com/richcar58/sqlexpr-congocc) for details. 


## Building SqlExprParserTester
    
Instructions assume Linux or a Unix-like operating system.

Building SqlExprParserTester is typically built automatically in an IDE like Eclipse, IntelliJ or Visual Studio.  To build from the command line, issue this command from SqlExprParserTester's top-level directory: 

>       mvn clean install
  
## Running SqlExprParserTester

The test programs found under the `src/test/java` directory can be run in an IDE or from the command line as standard [TestNG](https://testng.org/) unit tests.  The tests are essentially the same as those found in [sqlexpr-congocc](https://github.com/richcar58/sqlexpr-congocc), but here they pull the SqlExprParser binary from Maven Central.  
  
## Support

Support is on a best effort basis by creating GitHub issues on this repository.  The developer/maintainer can be contacted at *rcdev58 at pm.me*.

## Licenses

SqlExprParserTester is licensed under the MIT license. Some code was borrowed from the Texas Advanced Computing Center's [Tapis](https://github.com/tapis-project) project.   
