Windows PCI Compliance Pack
-----------------------------

The Windows PCI Compliance pack contains pre-configured tags, saved queries, and dashboards. These tags, saved queries, and dashboards have been created to help you maintain your PCI Compliance, this pack alone will not help you meet PCI Compliance, it's meant to be used in tandem with your Auditing Policies. Your Auditing Policies will determine what is and is not logged within your environment, in order to meet compliance, your Audit Policies should be configured to monitor both the logs and audit trails generated by your applications or systems, meaning you should be able to tell when and what a user accesses within your environment.

P.S. - I found this [blog](http://blog.jakeeliasz.com/2014/04/03/part-1-audit-trails-in-pci-dss-v3-0-logging-in-windows/ "blog") to be very helpful in the creation of this pack and it has additional information regarding the configuration of Windows Audit Policies to meet PCI Compliance.

This Community Pack contains the following:

* Dashboards: High level dashboards counting the number of invalid logins, admin accounts created, accounts locked out, Windows Audit Logs cleared, and changes to the Windows Auditing Policy within your entire environment. [Here](https://blog.logentries.com/wp-content/uploads/2016/03/WIN-PCI-Dashboard.png "Here") is what the PCI Compliance Pack dashboard would look like on a fresh account.

* Saved Searches: The searches which are powering the dashboards, and the searches to help you investigate the sources of invalid logins, admin accounts created, accounts locked out, Audit Logs cleared, and changes to the Windows Audit Policy. [Here](http://take.ms/1NP9k "Here") is what the saved searches look like, the "by host" saved searches are the searches you would use to investigate the source of Invalid Logins, Accounts Locked Out, etc.

* Tags and Alerts: Tags highlight instances of important Windows PCI events. These tags can quickly be configured as basic alerts, anomaly alerts and inactivity alerts to highlight spikes in important security events, password updates, and policy related events.