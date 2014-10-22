Richard Nghiem
---
**OBJECTIVE:**

A position where I can work with developers to release products quickly, utilizing automation and deployment tools.

**EXPERIENCE:**

**2012-current, Senior Operations Engineer, Path, San Francisco, CA**

* Grew the infrastructure to handle 10x the traffic.
* Worked with developers to release new features.
* Puppetized server tiers and wrote custom modules keeping new server configs in a consistant state.
* Wrote scripts to help streamline AWS server provisioning with notifications.
* Redesigned the various server tiers to be highly available.
* Migrated our EC2 setup from classic to VPCs.  All VPC configurations were automated with Ansible and commited to source control.
* Rewrote deploy scripts reducing deploy times from 2-3 hours to 2-3 minutes.
* Scaled out the single graphite setup to a 4 node sharded setup currently handling 280K metrics/minute.
* Created dashboards charting key metrics and site health using gdash and graphite.
* Replaced our process management system, supervisord, with runit due to various problems.
* Rebuilt the monitoring setup with more extensive checks and easier to manage configs under Puppet.

**2010-2012, Senior Operations Engineer, Zendesk, San Francisco, CA**

* Started as the 2nd operations engineer supporting a young start up company grow from a 8 server setup to over 200 servers serving 381M requests per week.
* Brought the monitoring system from a 3rd party managed Nagios setup to a fully automated in-house Icinga setup.  All new server bring ups were automatically monitored for both server and application health.
* Setup integration environments (dev, QA, staging) mirroring the production environment for developers and operations to test their code.  Integration environments were easily scaled as new project requirements were added using Chef.
* Transitioned the Ruby stack from version 1.8.7 to 1.9.3.  I used Chef to configure an environment where developers could rewrite small parts of the code to version 1.9.3 while older code still ran 1.8.7.   When I left, everything except for the mail processor had been moved to 1.9.3.
* Setup the Radar project, custom pubsub system, with the main developer over many revisions.  This was the first non-Ruby project written in NodeJS that needed a different deploy setup than our regular Ruby project deploys.  I adapted our single directory isolated Ruby setup using bundler gems to a NodeJS NPM isolated deploy.
* Upgraded the Radar project after a full code rewrite with almost zero downtime by working closely with the developer and understanding where the single points of failures were.
* Helped with the server and deploy setup of the Lotus project, a complete rewrite of the Zendesk front end, and the App Market project.  I setup a complete integration to production environment and worked with developers on environment bugs.
* Moved from our original Engineyard hosted setup to Rackspace.  Wrote scripts to check all services going through the Rackspace managed network gear for consistency.
* Expanded to a 2nd colocation at Ragingwire with a complete setup mirroring of all services.  Worked closely with the infrastructure engineer that made changes to Chef so it was multi-colo aware.  Worked out bugs so that future colo bring ups would be quicker.
* Ticket duty and wrote scripts for customer service advocates so they would be able to solve more tickets instead of escalating to operations.
* On call duty and tuned monitoring with the goal of less false alerts.
* Monthly scheduled maintenance duty where we brought down the entire site when there was major changes to be done.  Took part in almost every maintenance as the most senior operations engineer.

**2010-2010, Senior System Administrator, Sonoa/Apigee, Santa Clara, CA**

* Linux Server Operations.
* IT infrastructure.

**2006-2009, Senior System Administrator, Swivel, San Francisco, CA**

* Designed and setup the production environment.
* Setup a new collocation, network and server side.
* Moved the production setup from hosted to colocation with minimal downtime.
* Moved from bare metal setups to virtualized.
* Setup a dev, test and stage environment and using Capistrano for easy deploys.
* Packaged software to be deployed to multiple machines. 
* Evaluated AWS, EC2 and S3 to be integrated into our setup.

**2005-2006, System Administrator, Tagged, San Francisco, CA**

* Responsible for key services and UNIX servers.
* On call 24x7 with high availability and quick response time.
* Decommissioned collocation in preparation for liquidation.
* Consolidated the dev and stage environments using virtualization. 
* Monitoring of all services.
* Graphed key metrics for systems capacity and business trends.

**2001-2005, System Administrator, Guru/Unicru, San Francisco, CA**

* Responsible for all aspects of the company's UNIX infrastructure. 
* Systems implementation, maintenance, support and security.
* Storage with NetApp Filer and EMC Clariion.
* On call 24x7 for all production and corporate services.  
* Monitoring all systems

**2000-2001, System Administrator, WhyNot, Milpitas, CA**

* Responsible for all Windows desktops.
* Inherited Linux and Solaris server responsibilities.
* On call 24x7 for all emergencies.
