Migration Drivers
=================

An organization considering a Java EE server migration should carefully examine the motivation or combination of motivations behind the decision. These motivations have a potential impact on the strategic migration planning process.  They can influence the migration opportunities, choices, and trade-offs that must be made in the process. It is also important to understand the types of migrations that are possible as well as the potential deployment scenarios, as these may help proactively identify roadblocks and anticipate future needs.  

Common drivers deal with cost, increasing development innovation, and expanding business requirements.  Here is a list of the most common reasons for server migration.  

* Cost reduction
* Conformance to standards
* Datacenter consolidation
* Expanding business requirements
* Leveraging new technologies
* Mergers and acquisitions
* Replacement of retiring or discontinued software
* Capacity planning and performance
* Security and stability 

In many cases, a combination of motivations drive server migrations. Whereas no single motivation may be sufficient to warrant the move, the sum of the business objectives may be enough to justify the migration. In other cases, a single driver (such as cost savings) is greatly desired (or required) and sufficient to justify the migration.  

Whatever the particular drivers are, it is important to bear them in mind when planning migrations. Drivers help dictate priorities and methods when migrating. They are key to determining which migration scenario applies and how it should be deployed. For example, if a major driver is the desire to benefit from the latest features and capabilities, the migration project will need to delineate the features desired and determine which can be achieved by changing configurations and which will require updating source code.  

Potential Migration Scenarios
-----------------------------

Basic Web Appplication Migration

: Migrating basic web applications that were developed according to the servlet specification and Java EE specifications is the easiest and most cost-effective way to start migrations. It can be an excellent measure of the effort involved. If the applications were developed with a standards-based Integrated Development Environment (IDE) such as Eclipse, this will go quite smoothly. Many proprietary IDEs embed links to proprietary libraries and thus can add additional challenges to migration.
 
  Migrating a web application that is developed and deployed to a specific application server can be very simple or somewhat complicated depending on how proprietary the application architecture and dependencies are. Many web applications can simply be copied over and directly deployed to JBoss with no changes at all.  

Java EE Migration

: Migrating Java EE applications is in theory no more difficult than migrating pure web applications. However, the purpose of Java EE specifications is to facilitate the integration of multiple frameworks with diverse functionalities. This means that there will in practice be many mini-migrations involved.  

  If proprietary IDEs are used in the development of Java EE applications, these will often have the generated classes extend and implement proprietary classes and interfaces.  

Successfully Migrated Customers 
-------------------------------

* [Sprint Nextel](http://www.redhat.com/jboss/getunstuck/converts.html)
* [Mazda Austria](http://www.redhat.com/jboss/getunstuck/converts.html)
* [Heidelberg DRUCKMASCHINEN AG](http://www.redhat.com/jboss/getunstuck/converts.html)
* [Travel Channel](http://www.redhat.com/jboss/getunstuck/converts.html)
