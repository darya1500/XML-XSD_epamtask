# XML/XSD
To create [xml file](https://github.com/darya1500/taskepam/blob/master/bankdeposits.xml) that stores information about objects of certain subject area. To validate obtained xml-file,
it is necessary to develop the corresponding [xsd scheme](https://github.com/darya1500/taskepam/blob/master/bankdeposits.xsd). To parse xml document using [DOM](https://github.com/darya1500/taskepam/blob/master/src/main/java/by/epam/learn/daryatarasevich/bank/parsing/ParserDOM), [SAX](https://github.com/darya1500/taskepam/blob/master/src/main/java/by/epam/learn/daryatarasevich/bank/parsing/ParserSAX), [StAX parsers](https://github.com/darya1500/taskepam/blob/master/src/main/java/by/epam/learn/daryatarasevich/bank/parsing/ParserSTAX).
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
+ [date-time](https://github.com/darya1500/taskepam/blob/master/src/main/java/by/epam/learn/daryatarasevich/bank/action/DateConverter)
+ create at least 16 [entities](https://github.com/darya1500/taskepam/blob/master/src/main/java/by/epam/learn/daryatarasevich/bank/entity/Deposit) in xml document
+ organize parsers using the Builder template
+ use Log4J2 for logging
+ code should be [covered by tests](https://github.com/darya1500/taskepam/tree/master/src/test/java/by/epam/learn/daryatarasevich/bank)
