
<a target="_blank" href="https://bomonike.github.io/plc"><img align="right" width="100" height="100" alt="plc.png" src="https://github.com/bomonike/bomonike.github.io/blob/master/images/plc.png?raw=true" />
This is at <a target="_blank" href="https://bomonike.github.io/plc">https://bomonike.github.io/plc</a> from code within private repo <a target="_blank" href="https://github.com/bomonike/bomonike.github.io/blob/master/plc.md">https://github.com/bomonike/bomonike.github.io/blob/master/plc.md</a>

Diagrams such as this <a target="_blank" href="https://www.youtube.com/watch?v=IAhxYsMi4e8">Purdue "Automation Pyramid"</a> are from a PowerPoint file <a target="_blank" href="https://7451111251303.gumroad.com/l/pussom">here</a>.

This is based on <a target="_blank" href="https://www.hivemq.com/resources/smart-manufacturing-using-isa95-mqtt-sparkplug-and-uns/">ISA95</a> (International Society of Automation) which modeles data objects pushed to an enterprise Unified Namespace. <a target="_blank" href="https://www.wikiwand.com/en/articles/ANSI/ISA-95">ANSI-ISA95</a> is a large specification with many parts developed over many years.

<img alt="ignition-pyramid-1833x831.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726842630/ignition-pyramid-1833x831_y2qc08.png">

InductiveAutomation enables industrial companies to manage
* PLCs (Programmable Logic Controllers) that <strong>automate</strong> remote operation of equipment. Communication of inputs and outputs to and from each PLC is supervised by a
* SCADA (Supervisory Control and Data Acquisition) system.

Planning to coordinate minute-by-minute movement of material and work in process on the plant floor is done by a
* MES (Manufacturing Execution System).
Such a system makes more efficient use of limited capacity. MES reduces bottlenecks by calculating alternative routings in production.

Overall orchestration is done by "Top Floor" people using an
* ERP (Enterprise Resource Planning) system that does long-range planning (in industries with long lead time items) or complex bills of materials (BoM) needed on the shop floor, along with some form of associated shop orders in manufacturing industries.

* MRP includes most accounting functions, including general ledger, as well as inventory management, and resource and inventory planning.

These systems help with ISO 9001 certification and compliance with FDA CFR 21 Part 11 Medical Device Manufacturing.

At the shop floor or Field Level, RFID tags, barcodes, and weights and other measures are captured and displayed by a
* LIM (Laboratory Information Management) system.

There are also:
* Building Management Systems
* Warehouse Management Systems
* Logistics Management Systems to track and manage the movement of transportation vehicles carrying goods between vendors, plants, and customers.


<a target="_blank" href="https://libertyadvisorgroup.com/insight/manufacturing-execution-systems-erp-on-the-shop-floor/"><img src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726635389/MESP_attributes_vd4tom.webp"></a>

## Industrial?

"Heavy" industries need uninterruped power for monitoring and controlling real-time status of protected equipment:
* Electric power generation, transmission, and distribution
* Water and sewage
* Buldings, facilities, and enviornments
* Manufacturing
* Mass transit and traffic signaling

These systems need to be hardened" by implementing recommendations at:
https://www.cisa.gov/sites/default/files/2024-05/defending-ot-operations-against-ongoing-pro-russia-hacktivist-activity-508c.pdf
Controls include strong password, 3FA, VPN, log all access attempts, keep inventory & SBOM updated.

## Competition in the MES industry
PLC programming include:
* Wonderware (by Schneider)
* eazyworks.com
* WinCC
* iFix

* SAP
* Oracle
* Siemens
<br /><br />

### InductiveAutomation.com

https://ia.io/platform redirects to<br />
https://www.InductiveAutomation.com/
in Folsom, CA (Near Sacramento)
800-266-7798

People:
* Kevin McClusky is CTO
* <a target="_blank" href="https://www.linkedin.com/in/traviscox-automation/">Travis Cox</a>, Evangelist, created the AWS shell scripts
* Paul Scott, Training Content

Unlike legacy PLCs which use proprietary Assembly language, Ignition is customized using the Python language.

Unlike older competitors that use 15 inch monitors, InductiveAutomation clients display at HD (1920x1080 pixel) resolution on 22+ inch monitors.

InductiveAutomation charges by the number of servers installed for use by an <strong>unlimited number of clients</strong> at no additional licensing cost. <a target="_blank" href="https://www.youtube.com/watch?v=zH0m8Z0opyc">VIDEO</a>.

References:
* <a target="_blank" href="https://www.youtube.com/@YaskawaAmerica">VIDEO: IEC 61131-3 by Yaskawa</a>
<a target="_blank" href="https://www.youtube.com/@yaskawa">robotics</a>
* <a target="_blank" href="https://www.youtube.com/watch?v=3325bTcuPKQ">Top Requirements for an effective SCADA</a>
* https://www.youtube.com/watch?v=FDlxR2Ktoi4
* <a target="_blank" href="https://www.youtube.com/watch?v=R65XegwK3Bk">VIDEO: Anywhere</a>
* <a target="_blank" href="https://www.youtube.com/watch?v=0yKoEYPz5a4">VIDEO: Picking the right arch</a>
* <a target="_blank" href="https://www.youtube.com/watch?v=Qzskv9O_zh0">VIDEO: shows screens</a>


## Bookmark These Website URLs

* https://account.inductiveautomation.com/

* https://docs.inductiveautomation.com/docs/8.1/getting-started/
* https://docs.inductiveautomation.com/docs/8.1/intro
Ignition User Manual

* https://forum.inductiveautomation.com/
* https://www.linkedin.com/in/traviscox-automation/
* https://www.youtube.com/@InductiveAutomation

NOTE: The Ignition here is not related to the <a target="_blank" href="https://gazebosim.org/api/gazebo/6/index.html">Ignition Gazebo</a> libraries to develop robot and simulation applications.


## Security Alerts

America's Cyber Defense Agency, CISA (Critical Infastructure Security and Resilience) has released <a target="_blank" href="https://www.cisa.gov/search?g=inductive-automation-ignition#gsc.tab=0&gsc.q=inductive-automation-ignition&gsc.page=1">security alerts about Ignition</a> as part of its
Industrial Control Systems Advisories service for the world.


## Ignition servers

InductiveAutomation makes money by selling an annual <strong>license for each Ignition server</strong> (shown in blue in the middle of this diagram):

<a target="_blank" href="https://res.cloudinary.com/dcajqrroq/image/upload/v1726939517/ignition-mqtt-3024x1964_dx57of.png"><img alt="ignition-mqtt-3024x1964.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726939517/ignition-mqtt-3024x1964_dx57of.png"><br /><em>Click picture for full screen</em></a>

Ignition servers are called "<strong>Gateways</strong>" because industrial plants  typically take up a lot of territory, so there are both local and remote Ignition servers connected to a central Gateway.

Ignition makes uses of <a target="_blank" href="https://en.wikipedia.org/wiki/MQTT">MQTT</a> (Message Queue Telemetry Transport), a lightweight, publish-subscribe, machine-to-machine network protocol for message queuing.
MQTTt was created to monitor oil pipelines within the SCADA industrial control system (in SarkplugB format or add-in <a target="_blank" href="https://inductiveautomation.com/exchange/2670/overview">Vanilla Transmission</a>).

Ignition servers <a target="_blank" href="https://inductiveuniversity.com/courses/elective-studies/ignition-with-docker">run as containers within Docker</a> using the <tt>docker compose</tt> command. Licenses are <a target="_blank" href="https://inductiveuniversity.com/video/ignition-container-licensing">stored within the Docker image</a> along with <a target="_blank" href="https://inductiveuniversity.com/video/docker-secrets">secrets</a>. An <a target="_blank" href="https://inductiveuniversity.com/video/adding-an-smtp-server">SMTP server</a> using image dockage/mailcatcher on 1080 & 1025.


## Ignition Connections

The number of component Connections managed by Ignition servers are displayed the Gateway's Status GUI

<a target="_blank" href="https://res.cloudinary.com/dcajqrroq/image/upload/v1726946500/ignition-connections-2088x1308_hn2zum.png"><img alt="ignition-connections-2088x1308.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726946500/ignition-connections-2088x1308_hn2zum.png"></a>

<a name="PLCDrivers"></a>

## Device PLC Driver modules

The defining attractiveness of InductiveAutomation is that they provide a work-around to <strong>vendor lock-in</strong> which requires purchase of expensive priprietary solutions (at high profits for the vendor) called DCS (Distributed Control System). This vendor-driven approach requires much effort by each purchaser to integrate machines from among various vendors.

PLC (Programmable Logic Controller) <strong>devices</strong> control industrial equipment operation.

Each device is input into the database with a unique <strong>Tag</strong> identifier
along with various attributes with values.

Ignition has <a target="_blank" href="https://inductiveuniversity.com/videos/about-ignitions-modules/8.1">drivers for each manufacturer</a>, listed at

   <ul><a target="_blank" href="https://inductiveautomation.com/ignition/modules">https://inductiveautomation.com/ignition/modules</a></ul>

* Allen-Bradley (Logix 5000)
* Bentley Nevada
* GE
* Honeywell
* Logix
* Micro800
* Mitsubishi
* Omron (<a target="_blank" href="https://www.realpars.com/courses/omron-nx5-controllers">NX5 course</a>)
* Siemens (tags don't support browsing)
* Yokogawa

* ABB (Totalflow) ???
* Rockwell Automation ???

PROTIP: Don't select these modules during install unless you know you'll need them.

Many challenge this <a target="_blank" href="https://www.youtube.com/watch?v=QC3Bd2ynC7c">VIDEO</a>:
   * "PLCs are programmed with code."
   * "RTUs (Remote Terminal Units) have a web interface to lots of inputs, outputs, intelligence"

The cost of a license for Ignition depends on whether you want Perspective build, Siemens drivers, and voice notification. See:
<img alt="ignition-licenses.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1727723432/ignition-licenses_i5ztyn.png">


### Cloud Edition

Iginition is not a SaaS app like Salesforce.

<a target="_blank" href="https://www.youtube.com/watch?v=DCixhDisHQ8">VIDEO</a>:
The <a target="_blank" href="https://inductiveautomation.com/ignition/cloud-edition">Ignition Cloud Edition</a> obtained from the
<a target="_blank" href="https://aws.amazon.com/marketplace/pp/prodview-2rstgfnmrqc2o">AWS Marketplace</a> or <a target="_blank" href="https://azuremarketplace.microsoft.com/en-us/marketplace/apps/inductiveautomationllc1675268212292.ignition-cloud-edition?tab=Overview">Azure</a> installs on Ubuntu Linux servers from an (EC2 AMI) image, not as "serverless" functions.

<a target="_blank" href="https://inductiveuniversity.com/videos/cloud-edition-overview/8.1">IU</a>

"Auto-scaling" within a <a target="_blank" href="https://aws.amazon.com/solutions/partners/inductive-automation-ignition/">standalone AWS archicture</a> requires configuration of Auto Scaling Group (ASG) within a Bastion host in each of two Availability Zones. Configurations need to be <a target="_blank" href="https://aws-ia.github.io/cfn-ps-inductive-automation-ignition/">specified</a> in <a target="_blank" href="https://github.com/aws-ia/cfn-ps-inductive-automation-ignition/blob/main/scripts/creation_v2.sh">shell scripts</a> to define Security Groups, Public & Private subnets, NAT gateways, AWS KMS, CloudWatch, Amazon SNS, etc.

<img alt="ignition-aws-standalone-asg.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726757987/ignition-aws-standalone-asg_pxbwqq.png">

QUESTION: Can HashiCorp Terraform be used to stand up servers? That would enable identification of security and misconfiguration issues before resources are created.


## OPC (Open Platform Connect)

<a target="_blank" href="https://www.youtube.com/watch?v=0SrEJuONDyc">VIDEO</a>:
A big part of InductiveAutomation's value proposition is that they provide a way to obtain plant-wide <strong>visibility</strong> of the gamut of PLCs under various brands.


<a name="OPC-UA"></a>

Ignition's OPC-UA (Open Platform Communication United Architecture) <a target="_blank" href="https://inductiveautomation.com/ignition/modules/ignition-opc-ua">module</a> <a target="_blank" href="https://www.youtube.com/watch?v=3EREV8Q5PNU">VIDEO</a>:
* <a target="_blank" href="https://inductiveautomation.com/ignition/modules/opc-com">OPC-COM</a> for legacy OPC servers
* OPC-DA (Data Access) v2 & 3 for Windows
* OPC-HDA (Historical Data Access) v12
* OPC Tunneller ???


## Visibility from each and every location

InducativeAutomation enables the design of all PLC interactions to be defined from a single central Designer location by starting the Inductive Ignition <strong>Design Launcher</strong> app on their workstations (laptops).

QUESTION: What is "WrapperSimpleApp" that has a Java icon?

<a target="_blank" href="https://inductiveuniversity.com/courses/building-in-perspective">IU</a>:“Perspective” is Induction’s design IDE.

<a target="_blank" href="https://www.youtube.com/watch?v=_2ZqQ1Rc8xs">VIDEO</a>:
Touch panels provide a "HMI" (Human-Machine Interface) to PLCs (Programmable Logic Controllers).

There is less mistakes and waste when operators are assisted with a control panel such as this:
<a target="_blank" href="https://www.youtube.com/watch?v=T0WPK_lNQhM&t=1m46s"><img alt="ignition-fill-828x485.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726763341/ignition-fill-828x485_zvuizx.png"></a>


### Ignition Edge Edition

InductiveAutomation provides a "Touch Panel" that communicates with PLCs in their manufacturer's native protocol to access a 1-week data buffer.

<a target="_blank" href="https://inductiveuniversity.com/videos/edge-edition-architecture/8.1"><img alt="ignition-panel-727x374.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726763936/ignition-panel-727x374_aueufc.png"></a>

* <a target="_blank" href="https://www.youtube.com/watch?v=2ievolmYuw8">Raspberry Pi</a>

* <a target="_blank" href="https://www.youtube.com/watch?v=-vuYDBQoZKc">
What and why of Edge</a>


### Maker Edition

InductiveAutomation provides a free-forever edition for home automation.

* <a target="_blank" href="https://www.youtube.com/watch?v=ZkYZ1xTtzsg">VIDEO</a>: Maker Edition Install and Programming
* <a target="_blank" href="https://inductiveuniversity.com/videos/getting-started-with-maker/8.1">VIDEO</a>:
Maker Edition Install

<a name="StoreAndForward"></a>

## Store and Forward

Store and Forward engines are automatically created for configured database connections and remote history providers.

1. The Store and Forward Status page is at:

   http://localhost:8088/web/config/database.sandf?7#/

   It's where its Memory Buffer size and Disk Cache size can be edited.
   Actions include "Archive Disk Cache" and "Load Disk Cache".

1. Click "Details for

   http://localhost:8088/web/status/con.history?10


## Industrial Demo

* <a target="_blank" href="https://www.youtube.com/watch?v=0SrEJuONDyc" title="18m22s">VIDEO</a>:

Turn off Dark Reader on your browser.

This does not require installation locally.

<a target="_blank" href="https://demo.inductiveautomation.com/">https://demo.inductiveautomation.com</a> works 2 hours at a time.

View source to see that it uses React, Mobx, Moment, XHR.
All HTML on the page is loaded dynamically.

The app can be configured to <a target="_blank" href="https://www.youtube.com/watch?v=0SrEJuONDyc&t=14m56s">VIDEO: add a tint to an svg image</a>.


## Ignition Modules

Modules selected for install and <a target="_blank" href="http://localhost:8088/web/status/sys.modules?12">listed in the Gateway</a> (alphabetically):

* Alarm Notification
* Enterprise Administration
* <a href="#OPC-UA">OPC-UA</a>
* Perspective
* Reporting
* <a href="#SFC">SFC</a>
* SMS Notification
* SQL Bridge (defined in the Designer to support Transaction Groups : units of execution that perform actions such as storing data historically, synchronizing database values to OPC, or loading recipe values)

* Serial Support Client (not selected at install)
* Serial Support Gateway (not selected at install)

* Symbol Factory
* Tag Historian
* UDP and TCP Drivers
* Vision (an older front-end technology replaced by Perspective)
* Web Browser
* WebDev

There are also <a href="#PLCDrivers">PLC Driver modules</a> and Communication protocol modules (such as OPC-UA).

<a target="_blank" href="https://inductiveuniversity.com/video/filtering-modules">IU</a>: Modules displayed (filtered) are determined by the docker-compose.yml under services: gateway: enviornment: GATEWAY_MODULES_ENABLES=opc-ua,tag-historian,alarm-notification,logix-driver

https://inductiveuniversity.com/video/basic-structure-of-an-ignition-sdk-module


### Custom module development

<img alt="" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726828461/ignition-module-build_cgxfvh.png">

<a target="_blank" href="https://inductiveuniversity.com/courses/elective-studies/module-development-with-the-ignition-sdk">IU</a>:
Dev custom modules using the Ignition SDK written in <a target="_blank" href="https://medium.com/@ddmendes/using-kotlin-from-cli-on-mac-4560b5c70604">Kotlin</a> (developed by JetBrains) and Java run by the Azul.com OpenJDK Zulu JDK.

Use Git to clone https://github.com/inductiveautomation/ignition-sdk-training

The IDE recommended is IntelliJ IDEA free Community Edition.

The IMDC (Ignition Module Development Community) has code to Azure at
https://github.com/IgnitionModuleDevelopmentCommunity

* Scripting & expression Functions
* Components
* Tag providers
* Drivers

The <tt>build.gradle.kts</tt> config. file defines what project scope the module has. A letter defines each scope, such as "G" to com.inductiveautomation.ignition.examples.scripting.gateway.GatewayHook, C to ClientHook, D to DesignerHook, CDG to common.

<a target="_blank" href="https://inductiveuniversity.com/video/creating-a-new-module-gradle">IU</a>:
To build/generate SDK modules into a .modl file, Gradle.org is installed using:
https://github.com/inductiveautomation/ignition-module-tools

```
gradlew.bat clean build
```

```
gradlew.bat runCli --console plain
```

Each .modl file is actually a zip file containing a jar SNAPSHOT file for each scope, plus a XML manifest file named "module".

QUESTION: How sign custom modules?

<a target="_blank" href="https://inductiveuniversity.com/video/sdk-debugging-using-loggers">Logger objects</a> and messages for each scope.

<a target="_blank" href="https://inductiveuniversity.com/video/sdk-debugging-using-breakpoints">
Module debugging</a> makes use of a JDWP connection configured in /data/ignition.conf.


### Communication Protocol Modules

* TCP (using the HSMS standard, SEMI E37)

* <a target="_blank" href="https://www.youtube.com/watch?v=txi2p5_OjKU">MODBUS</a> is a protocol published by Modicon in 1979 (now owned by Schneider) when ASCII was used. It now make use of several media: RS-232 & RS485 serial, RS-422 TCP/IP Ethernet. It is called open becuase it is used by different PLCs. A master send sends requests for slaves to respond. A CRC error check in is added.

* RS-232 based protocol (using the SECS-I standard, SEMI E4), SECS/GEM is the <a target="_blank" href="https://en.wikipedia.org/wiki/SECS-II">Equipment Communications Standard E5</a> / Generic Equipment Model (standard E30) protocol defined by <a target="_blank" href="https://en.wikipedia.org/wiki/SEMI">SEMI (Semiconductor Equipment and Materials International)</a> for equipment-to-host data communications. In an automated fab, the interface can start and stop equipment processing, collect measurement data, change variables and select recipes for products.

* SMS (mobile) text notifications

* <a target="_blank" href="https://en.wikipedia.org/wiki/DNP3#:~:text=Distributed%20Network%20Protocol%203%20(DNP3,as%20electric%20and%20water%20companies.">DNP3</a> (Distributed Network Protocol 3) used by electric and water utilities
* <a target="_blank" href="https://en.wikipedia.org/wiki/IEC_61850">EC 61850</a> - communication protocols for intelligent electronic devices at electrical substations.
* <a target="_blank" href="https://en.wikipedia.org/wiki/BACnet">BACnet</a> - a communication protocol for building automation and control (BAC) networks that use the ASHRAE, ANSI, and <a target="_blank" href="http://www.iso.org/iso/iso_catalogue/catalogue_tc/catalogue_detail.htm?csnumber=37298">ISO 16484-5</a> standards protocol used by building automation and control systems for applications such as heating, ventilating, and air-conditioning control (HVAC), lighting control, access control, and fire detection systems and their associated equipment. The BACnet protocol provides mechanisms for computerized building automation devices to exchange information, regardless of the particular building service they perform.

* Send message to Lark

* ??? For interoperability among IoT devices, the <a target="_blank" href="https://en.wikipedia.org/wiki/Matter_(standard)">Matter</a> protocol under IP was developed by Amazon, Apple, Google, Samsung, and others with the Zigbee Alliance, at the <a target="_blank" href="https://en.wikipedia.org/wiki/Connectivity_Standards_Alliance">Connectivity Standards Alliance (CSA)</a>.
Version 1.0 of the spec and SDK was published 4 October 2022.
Matter uses as transport the <a target="_blank" href="https://www.threadgroup.org/What-is-Thread/Overview">Thread</a> <a target="_blank" href="https://en.wikipedia.org/wiki/Thread_(network_protocol)">IPv6 mesh protocol</a> for battery-powered devices,
supported by Apple iPhone 15 Pro, and all models of iPhone 16 and Google Pixel 9.


## Scaling with MQTT

The <a target="_blank" href="https://inductiveautomation.com/ignition/modules/eam">Enterprise Administration Module (EAM)</a>
enables management of many Ignition installations from one location.

<a target="_blank" href="https://inductiveuniversity.com/videos/ignition-system-architectures/8.1"><img alt="ignition-arch-3024x1964.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726629243/ignition-arch-3024x1964_enzi0p.png"></a>

Ignition communicates using the MQTT with central administration of permissions.

Ignition uses JDBC to store and retrieve data in SQL databases which use compression algorithms (called "Historian").

Ignition's Reporting Engine creates dynamic PDF files.

Ignition's Alarming system sends out notifications via voice, SMS, email.


## Customer usage

https://inductiveautomation.com/resources/customerproject

<a target="_blank" href="https://www.youtube.com/watch?v=2ievolmYuw8" title="from 2020">VIDEO</a>
Raspberry Pi Ignition Edge Install


### Using ChatGPT

<a target="_blank" href="https://www.youtube.com/watch?v=RverIFT0D_A">ChatGPT to create Views</a>



## Software Stack

<a target="_blank" href="https://inductiveautomation.com/ignition/modules">
<img alt="ignition-SoftwareStack-3200x1800.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726660786/ignition-SoftwareStack-3200x1800_llno0r.png"></a>
from <a target="_blank" href="https://assets.inductiveautomation.com/static/images/modules/SoftwareStack-Full@2x.f0b2ebbfd212.png">here</a>


## Ignition Modules

https://inductiveautomation.com/ignition/modules

<!-- img alt="ignition-integrations-1668x1338.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726626234/ignition-integrations-1668x1338_gnji26.png">
-->

* <strong>Gateway</strong> server executes modules, provides Launchers, then communicates with clients
Launched from the Gateway:
* <strong>Perspective Designer</strong> is inductiveautomation's HTML5-based design IDE to configure and build projects.
* Sessions are runtimes of the Perspective Module run in a browser.
* Vision clients are a legacy module superceded by Perspective.

<a target="_blank" href="https://inductiveuniversity.com/videos/what-is-ignition/8.1"><img alt="ignition-flow-2070x1304.png" src="https://res.cloudinary.com/dcajqrroq/image/upload/v1726626278/ignition-flow-2070x1304_yfsdlh.png"></a>

* Images ???
* Projects
* Tags is how Ignition uniquely identifies each OPC-UA object which communicates with PLCs.
* Database connections use utility code to reach databases using the JDBC (Java Database Communications) protocol. Python programs use a library to mimic how Java programs communicate.

* SFC (Sequential Function Charts) is Ignition's implementation of <a target="_blank" href="https://www.wikiwand.com/en/articles/IEC_61131-3">IEC 61131-3</a> specifications for graphical design used instead of Python. SFCs remain running like Python programs. <a target="_blank" href="https://docs.inductiveautomation.com/docs/8.1/getting-started/modules-overview/core-modules/SFC-module">User Manual</a>
   PROTIP: SFCs


## Dev Build

The current and prior releases (once per month) by QA Engineer <a target="_blank" href="https://www.linkedin.com/in/grossga/">Garth Gross</a> are at:
https://github.com/inductiveautomation/ignition-automation-tools/tags

Notice there is a different version for Ignition (8.1.39) and Perspective (2.1.39).

https://github.com/inductiveautomation/ignition-sdk-training

## Tutorials

https://inductiveuniversity.com/

1. Begin with first lesson at https://inductiveuniversity.com/courses/ignition/ignition-overview/8.1

   https://inductiveuniversity.com/videos/what-is-ignition/8.1

2. Create Account and verify email.
3. Take Topic Challenge


* 3 hr 49 min course "Building in Perspective" to create your first Perspective project.

* 1 hr 28 min course "Design Fundamentals" takes a deep dive into the world of visual design - common design patterns and philosophies.

* 46 min course "Advanced Styling in Perspective" for  tips and tricks to take your Perspective projects to the next level.

* 1 hr 15 min course "Module Development with the Ignition SDK" opens up Ignition to user/organization extensions and customizations with SDK module development.

1. Watch overview https://www.inductiveuniversity.com/video/what-is-ignition/8.1

   Ignition Designer tool

https://inductiveuniversity.com/courses/elective-studies


https://www.youtube.com/watch?v=ZkYZ1xTtzsg
Learning to Code Using Ignition!

## Install

The below is based on: https://docs.inductiveautomation.com/docs/8.1/getting-started/quick-start-guide/download-and-install

* <a target="_blank" href="https://www.youtube.com/watch?v=fPCbJSt9CBA">VIDEO</a>: Time-saving hacks

Ignition module <strong>skeletons</strong> work on Windows, Linux, macOS.

VIDEO: <a target="_blank" href="https://www.youtube.com/watch?v=spE6IpOU-2w">MQTT</a> demo project <a target="_blank" href="https://www.youtube.com/watch?v=2ievolmYuw8">on Raspberry Pi with Debian</a>

1. JDK does not need to be installed separately.
2. Install Python.
3. https://inductiveautomation.com/downloads/

   * macOS ignition-8.1.43-macos-64-installer.dmg Sep 17, 2024 was 1,644,383,679 bytes (1.64 GB on disk)
   * Linux  https://www.inductiveuniversity.com/videos/installing-ignition-on-linux/8.1
   * Windows  https://www.inductiveuniversity.com/videos/installing-ignition-on-windows/8.1

   CAUTION: On Windows, the path contains a space, so:<br />
   <tt>C:\Program Files\Inductive Automation\ignition</tt>

1. Installation Location on macOS:

   <tt>/usr/local/ignition</tt>

1. Installation Options: Custom (to install additional modules and adjust the default modules to install). Select from the <a href="#Modules">list of modules above</a>.
1. Install
1. Start Ignition Now
1. Uncheck Install Service.

   PROTIP: If on Windows, automatic start-up of the service is controlled at Start > Control Panel > Administrative Tools > Services > Ignition Gateway.

1. Finish and wait for the browser to pop-up.
1. Click "Standard Edition".
1. Click "I have read and agree with the terms and conditions".
1. In "Create a User", make up a Username and Password. Rootme

   PROTIP: <a target="_blank" href="https://inductiveuniversity.com/videos/password-reset-with-gwcmd/8.1">Password Reset with GWCMD</a> using <tt>./gwcmd.sh -p</tt> which restarts Gateway for new user/password entry.

1. Configure Ports Defaults:
   * HTTP Port: 8088
   * HTTPS Port: 8043
   * Gateway Network Port: 8060
1. Finish Setup.

   <a target="_blank" href="https://docs.inductiveautomation.com/docs/8.1/getting-started/quick-start-guide/launch-the-gateway">User Manual</a>

   ### Gateway LogIn & Status

1. Start Gateway. Wait.
1. Click "Yes, Enable Quick Start" for

   http://localhost:8088/web/home?3

1. Click the "Status" icon on the left menu.
1. Click "Log In".
1. Type the (Admin) Username you specified during install.


   ### Designer Launcher install

1. Get/Download the Designer Launcher,
1. Click blue "Download for macOS" : file designerlauncher.dmg.
1. Do not click green "Activate Ignition" unless you have purchased a license.
1. Switch to the macOS Finder.
1. Locate the file and double-click to open it.
1. Drag "Designer Launcher" and drop on the Applications folder icon.
1. Switch to Finder and right-click to Move it to "Move to Trash".
1. Navigate within the <tt>$HOME/Applications</tt> folder. Click the "Name" heading to sort by that. Type D.
   Notice its "Date Modified" is the date created, not the current date installed.

1. Double-click on "Designer Launcher" icon.
1. Click "Open" to confirm "downloaded from the internet".

1. Switch to click the red X at the upper-left to dismiss it.
1. Scroll down to Locations section and click the unmount icon to "Designer Launcher".

   ### Launch the Gateway


   ### Designer
   ### Vision Client Launcher
   ### Perspective Workstation
   ### Perspective Session Launcher

   ### Upgrade
   <a target="_blank" href="https://inductiveuniversity.com/videos/installing-or-upgrading-a-module/8.1">VIDEO</a>:
   At the Gateway:
1. Click the cog icon to "Config".
1. Login.
1. Modules

   https://localhost:8088/web/config/system.modules?5

   PROTIP: Module file names end with ".modi".

   The module is automatically signed with a certificate.

   QUESTION: Is there automatic upgrade of security patches?

   PROTIP: Upgrade of Ignition to several (not just the most recent) version.

1. Click "Backup/Restore" to Download Backup.
1. Some licenses do not permit major upgrade.

   ### Connect to a Device

   <a target="_blank" href="https://docs.inductiveautomation.com/docs/8.1/getting-started/quick-start-guide/connect-to-a-device">User Manual</a>

   <a target="_blank" href="https://docs.inductiveautomation.com/docs/8.1/ignition-modules/opc-ua/opc-ua-drivers/programmable-device-simulator">Programmable Device Simulator</a>


   ### Connect to a Database

   database MariaDB 4306

   ### Open the Designer
   ### Create Tags
   ### Add History to Tags
   ### Add Components - Perspective Session

1. Switch to the "My Designers" dialog.

1. https://docs.inductiveautomation.com/docs/8.1/getting-started/quick-start-guide

6. <a target="_blank" href="https://www.inductiveuniversity.com/videos/installing-ignition-on-mac/8.1">VIDEO</a>: Select the "Maker Edition", a "free, limited version of Ignition for personal, non-commercial projects.

7. Create a User
8. Start Gateway.
9. Don't save password on browser.
1. "Get Started" web page on Localhost.

1. Download Launchers.
1. Create a project.
1. Download add-on extensions.

   ### Stop & Start

   PROTIP: Add an alias for these commands in the OS CLI.

1. Stop the Gateway server.

   <tt>docker compose down -v</tt>

1. To start the Gateway server

   <tt>docker compose up -d</tt>

1. To stop the Gateway from starting upon startup, ???

## Config

1. Define the restore.gwbk file for backup.

## Dev

<a target="_blank" href="https://www.youtube.com/watch?v=ZkYZ1xTtzsg">VIDEO</a>:
Learning to code in Ignition

https://github.com/inductiveautomation
organization by <a target="_blank" href="https://www.linkedin.com/in/perryaj/">Perry Arellano-Jones</a> and <a target="_blank" href="https://www.linkedin.com/in/thirdgen88/">Kevin Collins</a>

* https://github.com/inductiveautomation/ignition-module-tools
* https://github.com/inductiveautomation/ignition-sdk-training uses Gradle processing Java and Kotlin

* <a target="_blank" href="https://github.com/inductiveautomation/kindling">Kindling</a>

https://github.com/orgs/ignition-devs/repositories?type=all


## OPC

Real-time OPC (Open Process Control) servers.

https://www.wikiwand.com/en/articles/Open_Platform_Communications

<a target="_blank" href="https://www.opcdatahub.com/WhatIsOPC.html#note1">Object Linking and Embedding OPC</a>

https://www.udemy.com/course/mastering-opc-ole-for-process-control/


## Sensors and Actuators

Several vendors provide industrial-strength sensors that monitor and actuators that control.

* <a target="_blank" href="https://www.youtube.com/@DpsTV">VIDEO</a>: <a href="_blank" href="https://www.DpsTele.com/">DPS</a> 800.693-0351

Low-cost microprocessors such as Arduino, Raspberry Pi, Intel NUC, Zima, etc.
provide a good way to train about general concepts.
But they don't have the weather, security, power-level proofing provided by industrial equipment.

## Projects

https://www.linkedin.com/pulse/mcu-iiot-inductiveautomation-ignition-wilson-mar-msc--azpic/

<a target="_blank" href="https://www.youtube.com/watch?v=RZW1PsfgVEI">VIDEO</a>:
Arduino PID Controller - From Scratch!  by Ian Car

<a target="_blank" href="https://www.youtube.com/watch?v=tEL3msXLE00">VIDEO</a>:
How PID Control Works
(the best explanation)

## Add-on packages

<a target="_blank" href="https://inductiveautomation.com/exchange/">inductiveautomation's Exchange</a> website provides (at time of writing) 442 add-ons for download.

Look for "Maker Edition Compatible" if you're running that.

A sample package is a zip file containing a README.md and MANIFEST file containing this example:
```
{
	"$schema": "http://json-schema.org/draft-07/schema#",
	"name": "Next Generation Dashboard",
	"ignition-version": "8.1.10",
	"version": "1.0.0",
	"modules": [{"name": "com.inductiveautomation.perspective"},{"name": "com.inductiveautomation.webdev"},{"name": "com.inductiveautomation.opcua"}]
}
```
Notice the file specifies the specific Ignition version.

The modules listed correspond to the folders at root:
* com.inductiveautomation.perspective
* com.inductiveautomation.vision is the older tech
* com.inductiveautomation.webdev

* com.inductiveautomation.opcua does not exist as a folder but mentioned in the project.json ???

In the Other folder are icons.zip and themes.zip.

The Projects folder holds a fonts.zip containing font files.

The core of the package is a file such as:

   <ul>dashboardKpi_20210922144324.zip<</ul>

Numbers in the file name is its date of creation.

The sample <tt>project.json</tt>
```
{
  "title": "KPI Dashboard",
  "description": "",
  "parent": "",
  "enabled": true,
  "inheritable": false
}
```
The ignition folder contains:
* designer-properties
* event-scripts
* global-props
* named-query
* script-python

The <tt>script-python</tt> contains folders:
* dashboard
* db
* KPIFramework/kpi
* tags

In each folder above is a resource.json such as:
```
{
  "scope": "A",
  "version": 1,
  "restricted": false,
  "overridable": true,
  "files": [
    "code.py"
  ],
  "attributes": {
    "lastModification": {
      "actor": "admin",
      "timestamp": "2021-09-21T21:51:47Z"
    },
    "lastModificationSignature": "bea61bf53cccfb3d2cb5e341bef1278049bd8ac4f44dc4b78bd948029b634872"
  }
}
```
The Signature is created during the build based on a Private key.

Right below copy and paste the icons from the ha_icons.svg file and save. Now we have new icons to play around with. The dashboard requires a few of these icons for the provided example.

Next, you need to import the project backup and tags provided by the resource. You can easily import both in the Ignition Designer. The tags are required for the example dashboard that is provided to show information.

Project backup and restoring from a project backup is referred to as Project Export and Import. Projects are exported individually, and only include project-specific elements visible in the Project Browser in the Ignition Designer. They do not include Gateway resources, like database connections, Tag Providers, Tags, and images. The exported file (.zip or .proj ) is used to restore / import a project.

    .zip = Ignition 8+
    ..proj = Ignition 7+

There are two primary ways to export and import a project:

    Gateway Webpage - exports and imports the entire project.
    Designer - exports and imports only those resources that are selected.

When you restore / import a project from an exported file in the Gateway Webpage, it will be merged into your existing Gateway. The import is located in:

Ignition Gateway > Configuration > System > Projects > Import Project Link

If there is a naming collision, you have the option of renaming the project or overwriting the project. Project exports can also be restored / imported in the Designer. Once the Designer is opened you can choose File > Import from the menu. This will even allow you to select which parts of the project import you want to include and will merge them into the currently open project.


The main view is Dashboard/Carousel. You can create a page (in Perspective page configuration) that uses that main view. You can easily configure the dashboard to modify the widgets and tags they point to. Simply open up the Carousel view and take a look at the Carousel component's "views" property.

Basically, the carousel can have multiple pages since views is an array. Each page uses the Dashboard/Dashboard view. The parameters dictate the widgets shown. The resource provides a set of standard widgets. You can easily create your own. The Standard widget is the most used. There are a ton of configuration options. Play around with the parameters to get an idea. If you want to see what parameters are possible, check out the widget view.


Ignition can export and import Tag configurations to and from the JSON (JavaScript Object Notation) file format. You can import XML (Extensible Markup Language) or CSV (Comma Separated Value) file formats as well, but Ignition will convert them to JSON format. Tag exports are imported in the Designer. Once the Designer is opened you can click on the import button in the Tag Browser panel.

<hr />

## Diagnostic Bundle

1. Unzip

   Folders in the bundle:

   * gateway-info.json
   * gateway-network-live-diagram.json
   * jetty-server-dump.txt
   * metrics.idb
   * system_logs.idb
   * thread-dump.json
   * wrapper.log


## Tutorials

* <a target="_blank" href="https://www.youtube.com/@ITandAutomationAcademy">IT and Automation Academy</a>

<a target="_blank" href="https://www.youtube.com/watch?v=GD6WKPFG0T0">Remote monitoring design tips</a>

https://www.youtube.com/watch?v=z935clBMJYU
The IP (ingress Protection) rating of devices is defined by International Standard EN 60529. The 2-digit code defines the result of tested resistance to solids and liquids.

https://www.youtube.com/watch?v=aYltp_iM6VA
6 Key Terms in Upstream Oil and Gas Automation (PLC vs RTU in the Electric/Digital Oilfield)
by Kimray
