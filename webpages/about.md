---
title: About
path: /about
summary: What is Brick? How does Brick compare to X?
show_on_navbar: false
---

## What is SARGON?

SARGON (SmArt eneRGy dOmain oNtology)is an open-source effort to define semantic descriptions of the ** smart assets** in building automation and smart grid and **the relationships between them**.
SARGON consists of an **extensible dictionary** of terms and concepts in and around building and smart grid, a set of **relationships** for linking and composing concepts together, and a **flexible data model** permitting seamless integration of SARGON with existing tools and databases.
Through the use of powerful Semantic Web technology, SARGON can describe the broad set of Devices and custom features, assets and subsystems found across the building stock in a consistent matter.

The source code for SARGON, this website, and related tools are available on **[GitHub](https://git.rwth-aachen.de/EBC/Team_BA/projects/n5geh/n5geh.datamodel/-/tree/master/)**.

![Brick Model Example](/images/protege.png)

## How Does SARGON applied to the Energy Domain?

An Ontology represents the description of knowledge from an interest field. The main purpose of ontologies is to represent the objects semantics from a given domain. This objective is achieved by assigning the objects to classes and by describing those, using properties. According to the model of the used ontology, such descriptions are managed by different restrictions. To enable such a description, it is necessary to formally specify components such as individuals (instances of objects), classes, attributes and relations as well as restrictions, rules and axioms. As a result, ontologies do not only introduce a sharable and reusable knowledge representation but can also add new knowledge about the domain.
Some of the major characteristics of ontologies are that they ensure a common understanding of information and that they make explicit domain assumptions. As a result, the interconnectedness and interoperability of the model make it invaluable for addressing the challenges of accessing and querying data in large organizations. Also, by improving metadata and provenance and thus allowing organizations to make better sense of their data, ontologies enhance data quality.

## From ontology to CIM?

One of the main features of ontologies is that, by having the essential relationships between concepts built into them, they enable automated reasoning about data. Such reasoning is easy to implement in semantic graph databases that use ontologies as their semantic schemata.
What’s more, ontologies function like a “brain”. They work and reason with concepts and relationships in ways that are close to the way humans perceive interlinked concepts.
Ontologies allows to capture data in a way that makes their relationships become visible, thanks to the use of Unified Modeling Language (UML). The (UML)  is a general purpose, developmental, modeling language in the field of software engineering that is intended to provide a standard way to visualize the design of a system. UML does not offer a lot of tools to express relationships between objects. Everything that is not an aggregation or generalization is swallowed by the very general term "association". Here's where ontologies use semantics. Semantics is about relationships between signifiers (e.g. words).
Data models are usually defined by UML diagrams. For example, the electrical Common Information Model (CIM)  is defined and maintained as a UML model. It defines a common vocabulary and basic ontology for aspects of the electric power industry.
The CIM models the network itself using the so called “wires model”, which describes the basic components used to transport electricity. Measurements of power are modeled by another class. These measurements support the management of power-flow at the transmission level and by extension, the modeling of power through a revenue meter on the distribution network.
The CIM is also used to define messages for the wholesale energy market with the framework for energy market communications, IEC 62325. The European style market profile is a profile derivation from the CIM to harmonize the energy market data exchanges in Europe .
Ontologies can be described in Ontology Web Language (OWL), a language used for knowledge representation (KR) in a semantic perspective. OWL is a set of markup languages which are designed for use by applications which need to process the content of information, instead of just presenting information to humans.
The OWL ontology describes the hierarchical organization of ideas in a domain, in a way that can be parsed and understood by software. OWL has more facilities for expressing meaning and semantics than XML, RDF, and RDF-S, and thus OWL goes beyond these languages in its ability to represent machine interpretable content on the Web.
In OWL, it is possible to define new relationships between things. The example below defines a property "madeFromGrapes" which points from a class "wine" to a class "wine grapes". Of course, this "madeFromGrapes" is a much better description of the relationship between a wine and a type of grapes than a simple association.
In a UML diagram the relationship between a man and a dog and a wine and a grape look all the same. OWL, on the other end, allows to define these relationships more specifically, which is important if information should be processed by a computer, as the more information a computer can use for its processing, the better. With data models expressed in UML the depth of information can be very limited. in this respect.


## SAREF: description and benefit from its usage
In the future, domestic and industrial appliances will be intelligent, networked smart devices, forming complete energy consuming, producing and managing systems, based on the integration of products from different vendors and vertical industrial sectors. 
The need for all these connected appliances to be able to communicate among themselves and with the service platforms needs to be addressed. This requires open interfaces. Interoperability is thus a key factor in creating an IoT ecosystem, and the availability of a standardized solution, along with related test suites, will be the essential enabler of the IoT. 
To ensure such systems are technically and commercially successful – and widely adopted – it must be possible to combine appliances from different vendors. These systems will also need to be able to communicate with service platforms from different energy service providers in order to manage and control energy usage.
There have been several efforts in terms of ICT standardization in smart home, energy and IOT like CEN, CENELEC, ETSI, IEC, etc. But most of this standardizations effort focus on a specific aspect of smart system for example CENELEC (European Committee for Electrotechnical Standardization)  perform standardization work to enable domestic appliances improve functionality through the use of network communication like smart grids, smart homes and smart networks.  CEN (European Committee for Standardization)  defines a standard in the IoT environments that focuses on the interfaces between edge data capture technologies and the IoT. However, ETSI (European Telecommunications Standards Institute)  gives us a global standard for ICT and with the support commission, ETSI developed SAREF. 
The “Smart Appliances REFerence” (SAREF)  ontology is a shared model of consensus that facilitates the matching of existing assets (standards/protocols/data models/etc.) in the smart appliances' domain. The SAREF ontology provides building blocks that allows separation and recombination of the different part of ontology depending on specific needs. 
The starting point of SAREF is the concept of Device (e.g., a switch). Devices are tangible objects designed to accomplish one or more functions in households, common public buildings or offices. 
The project covers the following appliances:
   
     Home and buildings sensors (temperature, humidity, energy-plugs, energy clams, energy meters, water-flow, water quality, presence, occupancy, air monitors, environmental sensors, CO2 sensors, weather stations, etc.) and actuators (windows, doors, stores). Sensors belonging to appliances are treated individually, White goods, as classified by CECED ,Rinsing and Cleaning , Cooking and Baking , Refrigerating and Freezing, Vacuum Cleaning , Washing and Drying, HVAC; heating, ventilation, and air conditioning, plumbing, security and electrical systems, as classified by Eu.bac, Lighting, with use cases as defined by LightingEurope (f.k.a. ELC), Micro renewable home solutions (solar panels, solar heaters, wind, etc.

The SAREF ontology offers a list of basic functions that can be eventually combined in order to have more complex functions in a single device. It is the core semantic model for smart appliances, which contains the data elements that are used in more than one domain. 
Since smart appliances can be used in and come from several domains, it is possible that specific data elements for a certain domain are not defined in SAREF. To be able to handle these additional data elements and provide a specific domain with a semantic model that fits all the needs of that domain, there is the possibility to create extensions to SAREF.
The modular conception of the ontology allows the definition of any new device based on building blocks describing functions that devices perform. Furthermore, SAREF can be specialized to refine the general semantics captured in the ontology and create new concepts. The only requirement is that any extension or specialization may comply with SAREF.

### SAREF in energy domain
Concerning Smart Appliances SAREF extension investigation in the energy domain, direct inputs from EEBus  and Energy@home  have been included in SmartM2M developments where Energy, Environment and Building sectors are now part of normative work. SAREF4ENER  is meant to enable the (currently missing) interoperability among various proprietary solutions developed by different consortia in the smart home domain. By using SAREF4ENER, smart appliances from manufacturers that support the EEBus or E@H data models will easily communicate with each other using any energy management system at home or in the cloud. 
Towards this aim, SAREF4ENER should be used to annotate (or generate) a neutral (protocol-independent) set of messages to be directly adopted by the various manufacturers or mapped to their domain specific protocols of choice. SAREF4ENER focuses on demand response scenarios, in which customers can offer flexibility to the Smart Grid to manage their smart home devices by means of a Customer Energy Manager (CEM). 
The CEM is a logical function for optimizing energy consumption and/or production that can reside either in the home gateway or in the cloud. Moreover, the Smart Grid can influence the quantity or patterns of use of the energy consumed by customers when energy-supply systems are constrained, e.g. during peak hours. These scenarios involve the following use cases:
  
  •  	Configuration of devices that want to connect to each other in the home network, for example, to register a new dishwasher to the list of devices managed by the CEM.
  
  •  	Smart energy management/ (re-)scheduling appliances in certain modes and preferred times using power profiles to optimize energy efficiency and accommodate the customer's preferences
 
  •	    Monitoring and Control of the start and status of the appliances;
  
  • 	Reaction to special requests from the Smart Grid, for example, incentives to consume more or less depending on current energy availability, or emergencies that require temporary reduction of the power consumption.
These use cases are associated with the user stories according to the IEC TR 62746-2:2015, it describes systems interface between the customer energy management system and the power management system. 
Therefore, there is common agreement between Industry and Research that there is a concrete possibility to proceed with the extension of the SAREF ontology to the subset of this standard related to devices and appliances.

### Considerations on the necessary SAREF extention

The energy sector is experiencing a continuous transformation: data-driven services and functionalities depend more and more on smart devices, which communicate between each other an increasing amount of data. This digitalization process is expanding to domains never considered in this transformation, for which a suitable representation of the system according to the presented SAREF ontology constitutes a valuable advance.
A certain number of domains have been identified as possible targets for extending SAREF. In particular, with reference to the activities conducted in the research projects FISMEP and “National 5G Energy Hub” , the goal of creating SAREF extension in smart energy is to consider the distribution electrical grids and building energy automation domains. 
The initial SAREF extension in smart energy is based on a limited set of use cases and existing data models identified within available initiatives that are summarized below:

   •	Automation of medium voltage distribution grids is considered in the proposed activity, in particular considering the inclusion of Direct Current (DC) technology for which the grid is operated as hybrid AC-DC electrical network. Currently, the standard IEC-61850 constitutes a well-received reference for the automation of distribution grids. The proposed extension consists in reformulating the data structure used in IEC-61850 according to an ontology description, as well as introducing devices specifically related to hybrid AC/DC grids, as power converters or DC switches.
   •    Phasor Measurement Units (PMUs) find more and more application in the monitoring and control of the electrical grid, not only in the transmission networks but also in the distribution ones. The PMUs interaction with the connected devices, as well as the data-driven applications that exploits the obtained measurements, constitute a worthwhile field for the SAREF expansion.
    
   •	The control of energy provision in buildings (as gas, electricity, hot water, etc.) and its optimization involves the deployment of building energy management (BEM) systems, which rely on the interaction with smart meters and actuator devices for the effective operation of each functionality. Moreover, the user involvement in the overall process is an undeniable constituent, which has to be included in the ontology representation of this domain.
   
   •	In order to optimize the overall energy management, the utilities have to expand the energy control to the entire city district, as building agglomeration. New strategies are being developed, considering also the increasing deployment of Distributed Energy Resources (DERs) and the new role of prosumers in the energy market.
   
   •	The proposed SAREF expansion targets also the interaction between the energy management of building/districts and the electrical automation, considering the control functionalities and the data/measurements that involve the combination of both these aspects.

Device Supported         | **SARGON**  | **SAREF**
-------------------------|-----------|----------
HVAC Systems             |  **yes**      |   no
Smart Grid               |  **yes**      |   no
Lighting Systems         |  **yes**      |   no
Electrical Systems       |  **yes**      |   no
Spatial Information      |  **yes**      |    no
Sensor Systems           |  **yes**      |  **yes**
Control Relationships    |  **yes**      |   no
Sequential Relationships |  **yes**      |    no
Formal Definitions       |  **yes**      |    **yes**
<br></br>


