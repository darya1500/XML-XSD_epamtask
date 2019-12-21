# XML/XSD
To create xml file that stores information about objects of certain subject area. To validate obtained xml-file,
it is necessary to develop the corresponding xsd scheme. To parse xml document using DOM, SAX, StAX parsers.
## TASK
### Bank deposits
+ Name - name of the bank.
+ Country - country of registration.
+ Type - type of deposit (on demand, periodic,calculated,accumulation,saving,metal).
+ Depositor -name of the depositor.
+ Account id - account number.
+ Amount on deposit - the amount on the deposit.
+ Profitability - annual percentage.
+ Time constraints - deposit term.
The root element should be called Banks.
### Requirements
Use:
+ attributes required & optional
+ enumeration
+ patterns and limits
+ type ID
+ setting attribute values by default
+ type extension (imitation of inheritance)
+ date-time
+ create at least 16 entities in xml document
+ organize parsers using the Builder template
+ use Log4J2 for logging
+ code should be covered by tests
