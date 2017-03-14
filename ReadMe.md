# GWMSIST: RDBS | Lab2: MariaDB * AWS

Objective: In this lab we will work through many of the SQL commands discussed in lecture.  As a guide to using these commands we will use our textbook on MariaDB (mostly the same as MySQL).  You will be using the Amazon RDS instance created in Lab 1

## Deliverable

TODO: History log from your mysql command line session.

## Usage

TODO:  For this lab, work through these sections in the *MariaDB Crashcourse* textbook.  Note: in some of the later labs you may get an error that a table already exists.  The reason is the batch files we ran in Lab 1.  Ignore the error and keep moving forward.

## History

TODO: Launch AWS instance terminal-output with termina-output according to the following convention:

`./mysql -h [Your AWS-Endpoint] -P 3306 -u [Your User-name] -p --tee=[Desired name of terminal-output history].txt`

Example:

`./mysql -h bucephalus.cg8qnwa72czw.us-west-2.rds.amazonaws.com -P 3306 -u alexander -p --tee=alexanderjsingleton_mysqlout_1.txt`

## MariaDB Crash Course Chapters

* Chapter 4: Retrieving Data

* Chapter 5: Sorting Retrieved Data

* Chapter 6: Filtering Data

* Chapter 10: Creating Calculated Fields

* Chapter 11:  Using Data Manipulation Functions

* Chapter 12:  Summarizing Data

* Chapter 13:  Grouping Data

* Chapter 14:  Working with Subqueries

* Chapter 15:  Joining Tables

* Chapter 19:  Inserting Data

* Chapter 20:  Updating and Deleting Data

* Chapter 21:  Creating and Manipulating Tables

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## References

1. According to [MariaDB documentation](https://mariadb.com/kb/en/mariadb/aria-faq/), the MySQL-version (not exatly MariaDB with this lab) featured on the AWS ec2 instance is deprecated- so use `ENGINE=InnoDB` in lieu of `ENGINE=Aria`;
