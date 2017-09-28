# MavenSampleOracleJdbc
Maven sample project for use a Oracle JDBC Driver

# how to use on local environment

change ${OTN_USERNAME} by your Oracle login in test/mvnsettings.xml file

change ${OTN_PASSWORD} by your Oracle password in test/mvnsettings.xml file

```
mvn clean install --settings test/mvnsettings.xml
```

# how to use on travis-ci

![TravisCi](/screenshots/travis-ci.png)

# Continuous Integration status
[![Build Status](https://travis-ci.org/sgrillon14/MavenSampleOracleJdbc.svg?branch=master)](https://travis-ci.org/sgrillon14/MavenSampleOracleJdbc)

# License

[![license](https://img.shields.io/github/license/sgrillon14/MavenSampleOracleJdbc.svg)](https://github.com/sgrillon14/MavenSampleOracleJdbc/blob/master/LICENSE) + Oracle Technology Network License Agreement, See LICENSE for details