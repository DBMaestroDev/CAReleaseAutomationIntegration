![DBmaestro logo](http://www.dbmaestro.com/wp-content/uploads/2013/02/main-logo1.png)

# DBmaestro CA Release Automation Integration

Introduction
------------

DBmaestro TeamWork, the leading DevOps for Database solution, offers integration with CA Release Automation. CA Release Automation helps companies address some of their most critical DevOps challenges by providing a continuous delivery solution that helps improve visibility across the enterprise’s deployment chain.

DBmaestro TeamWork integrates with CA Release Automation by enhancing it with the required functionality that includes database build & deployment tasks.

Installation
------------

1. Open CA Release Automation.
2. Launch Release Operations Center.
3. Login with a user with access to Administration.
4. Click Administration -> Action Management.
5. Tab to Installed Packs by clicking on header.
6. Click "Import" on top right of tab.
7. Select Extracted DBmaestro Jar, Open.
8. Wait for process to complete.
9. Action pack should now be installed for your use.

Troubleshooting
---------------

* If you get Timeout from Nolio side
	- please check the timeout on Nolio
	- you can go to settings and uncheck Pause in failure, but please note that it will continue also on real failures

* Note that 'DBMS' field is not in use

* Can't run twice actions because we will get error: Label already exists.There is no Dinamyc parameters

* For optional fields, values with spaces must be surrounded with quotation marks. for example: "this is a field value".



Maintainers
------------

DBMaestro development team. For any issue please visit: http://www.dbmaestro.com/support/contact-support/


