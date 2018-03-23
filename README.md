# alida-pom
This project provides the Maven parent POM file for all projects linked to [**Alida**](http://www.informatik.uni-halle.de/alida), the Advanced Library for Integrated Development of Data Analysis Applications. The library defines a concept for designing libraries and toolkits in data analysis. It supports and simplifies integrated algorithm development by inherently joining algorithm implementation, automatic analysis process documentation and fully generic generation of user interfaces.

This parent POM file contains all basic definitions and declarations relevant for all projects directly or indirectly related to the Alida library, e.g. for the Alida core projects [**alida**](https://github.com/alida-hub/alida) and [**alida-xml**](https://github.com/alida-hub/alida.xml) as well as for projects being built on top of Alida like [**mitobo**](https://github.com/mitobo-hub/mitobo). Besides providing general information about Alida the parent POM file particularly includes settings for versions of dependencies and Maven plugins used in the context of Alida's Java implementation to avoid version conflicts and inconsistencies.

The main project homepage of Alida is located [**here**](http://www.informatik.uni-halle.de/alida), the source code can also be found on [**Github**](https://github.com/alida-hub/alida).

Note that alida-pom releases on Github are GPG signed, you can get Alida's public key for verification by following [**this link**](https://pgp.mit.edu/pks/lookup?op=get&search=0x72C17EF19A4D2F66).
