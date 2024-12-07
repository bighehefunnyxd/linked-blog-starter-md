The data reduction approach attempts to reduce the amount
of detailed information considered to focus on the most critical, interesting,
or abnormal items (e.g., highest cost, highest risk, largest impact, etc.). It
does this by filtering through a large set of data (perhaps the total
population) and reducing it to a smaller set that has the vast majority of the
critical information of the larger set. The data reduction approach is done
primarily using structured data—that is, data that are stored in a database or
spreadsheet and are readily searchable.

Data reduction involves the following steps (using an example of an
employee creating a fictitious vendor and submitting fake invoices):
	1. *Identify the attribute you would like to reduce or focus on.* 
		1. For example, an employee may commit fraud by creating a fictitious vendor and submitting fake invoices. Rather than evaluate every employee, an auditor may be interested only in employee records that have addresses that match vendor addresses.
	2. *Filter the results.* 
		1. This could be as simple as using filters in Excel, or using the WHERE phrase in a SQL query. It may also involve a more complicated calculation. For example, employees who create fictitious vendors will often use addresses that are similar to, but not exactly the same as, their own address to foil basic SQL queries. Here the auditor should use a tool that allows fuzzy matching, which uses probability to identify likely similar addresses.
	3. *Interpret the results.*
		1. Once you have eliminated irrelevant data, take a moment to see if the results make sense. Calculate the summary statistics. Have you eliminated any obvious entries? Looking at the list of matching employees, the auditor might tweak the probability in the fuzzy match to be more or less precise to narrow or broaden the number of employees who appear.
	4. *Follow up on results.*
		1. At this point, you will continue to build a model or use the results as a targeted sample for follow-up. The auditor should review company policy and follow up with each employee who appears in the reduced list as it represents risk.