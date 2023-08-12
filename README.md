# Salesforce-Apex-PMD
Salesforce PMD Rule Set Definition File

Run the below lines in the cmd prompt to get the Code scan result as a report.

pmd.bat -d "<sfdc folder directory location" -f html -R "<Apex PMD Ruleset file location>\<apex rule set filename>.xml" -reportfile "<your desired destination file location>\<reportname>.html"
