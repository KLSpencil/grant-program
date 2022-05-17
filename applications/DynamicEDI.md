# VeChain General Grant Application 

## Project Overview 

- Project: GetDynamic
- Team Name: AerodynamicData 
- USDT Payment Address: 0x8D4AA616E759058A9aD5cD4F43F4CbD23A7A6Baf
 

### Overview

GetDynamic is a blockchain EDI(Electronic Data Interchange) Messaging  system focused on automating data exchange between business partners.  The app will integrate with existing on-prem and cloud based ERP (Enterprice Resource Planning) database platforms and allow pre-defined and custom scripts to automatically send and receive data. The integration tool is designed to quickly and easily allow for any database to be connected for both sending and receiving.  Standard EDI formats will be supported but not required to be followed.  

This project was born out of my 15 years of experiences as an ERP consultant in the aerospace industry. Many companies have the same issues with data 
and yet do not have any easy way of exchanging the data they need.  Most companies are still exchanging small amounts of data via phone and email or also using legacy centralized systems at great cost.  The high cost of existing EDI vendors sets a high cost of entry for small to medium sized businesses to take advantage of such tools. GetDynamic significantly reduces that transcation cost while still providing a private and secure service making this kind of automation available to a wider array of companies. The app will integrate VIP191 fee delegation to eliminate the need for users to own any crypto themselves however transactions can be paid from client wallet without having a subscription.   Transaction costs will be billed to customer on a monthly basis via smart contract integration. VIP192 and VIP181 are intended to be used for future features.  


### Project Details

Our project is primarily based on Python, Django and Postgres.  Other technologies being used include Go, C#, Docker, Javascript,  
VMWare, IPFS, Truenas, and Cloudflare. 

We expect the teams to already have a solid idea about the project's expected final state.
Therefore, we ask the teams to submit (where relevant):
- Mockups/designs of any UI components
- API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic

### Ecosystem Fit
Within Vechain there are not any projects that we are aware of that are similar.  On other chains we have found messaging systems but have not found any that focus on connecting to ERP systems for data exchange.   Companies providing legacy EDI systems include TrueCommerce, Seeburger, and IBM Sterling.  We believe that our app fits well within the Vechain ecosystem as it will provide an on-ramp for companies to leverage existing infrastructure in accessing and taking advantage of modern distributed ledger technology.


## Team 

### Team members & Contributors
- Ryan Realivasquez (Founder, Full stack Development) 
- Matt Haydon (Cofounder, Web Development, Marketing ) 
- Genaro Coronel (Full Stack Development) 
- Oleg Tropinin (Full Stack Development) 
- Pietro Race (Advisor) 

### Team Website

- https://getdynamic.app
- 
### Team's experience

Please describe the team's relevant experience. If the project involves development work, then we'd appreciated it if you can single out a few interesting codes commits made by team members on their past projects. 

Ryan Realivasquez is the primary founder of GetDynamic.  He brings to the table over 15 years of consulting experience delivering implementations and support of ERP systems in the aerospace industry.  It is during this time consulting that he identified the need for a lower cost and more widely available system for exchanging data between companies.   While EDI systems already exist DynamicEDI is born out of listening to users of these existing systems and their needs and interests.  Privacy.  Simplicity. Cost.  Ryan launched development of the app, has researched and defined the infrastructure technologies to be used, defined the features and product roadmap, and has self funded the  engagement of professional developers to complete initial development. 

Matt Haydon is a cofounder of DynamicsEDI.  He has past experience launching several small businesses and is an influencer within the blockchain space operating successful social media communities.   Matt is also contributing to development of our app by focusing on designing and building the UX in our interfaces as well as planning and when it is time executing on our web marketing plan.  

Genaro Coronel is our principal developer. He has added several major features to the infrastructure of our app and will be our primary smart contract seveloper as well. He is responsible for coding our IPFS-Cluster storage backend, Dockerizing the infrastructure, and connecting the app to the Vechain network.  

Oleg Tropinin has contributed to early development efforts and will be rejoining us for future development.  He has been responsible for our initial Vechain integration, and web app infrastructure setup. 

Pietro Race is an advisor who has been working with us to help ensure development meets client's requirements.   Pietro has over 20 years working in the Aviation Industry as a software consultant and currently operates the leading consultancy in the aviation industry for ERP Integrations and Operations consulting. We fully intend to leverage his relationships in expanding our reach. 



### Team Code Repos
Will provide via DM

### Team LinkedIn Profiles

- https://www.linkedin.com/in/ryanrealivasquez/
- https://www.linkedin.com/in/matthaydon/

## Development Roadmap 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an <b>example roadmap</b>. For each milestone:

- Please indicate the milestone duration, workload in terms of full-time equivalent (FTE) and cost. 
- Please be sure to include a specification of the software. The level of details must be high enough so that we are able to verify that the software meets the specification.
- Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
- Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
- Please commit to providing dockerfiles for the delivery of your project.


### Example Roadmap for a dApp Application

### Overview

|  | Milestone 1 | Milestone 2 | Milestone 3 | Milestone 4 | Total |
| - | - |- | - | - | - |
| Estimated Duration |Completed | 60 d | 30 d | 30 d | 120 d |
| Full-time equivalent (FTE) | 2 | 1 | 3 | 3 | 3 |
| Cost (up to $ 30,000) | $ 7,500 | $ 10,000 | $ 7,500 | $5,000| $ 30,000|

#### Milestone 1 — Infrastructure, Backend, WebApp,  Website  

This first milestone represents work in-progress or already completed.  We ask the foundation to please review our submitted work, validate completion of this 1st milestone, and deliver payment upon validation.   This will enable us to launch and move forward on completion of the remaining milestones. 

| 1a. | Infrastructure  | We are asking for assistance with the first year of infrastructure service costs.  This covers a primary and backup VPS service each operating Vechain testnet and mainnet nodes, on-prem and cloud storage services for the network, data backups, and monitoring. Internal production and test network topology is configured for security with current generation enterprise quality gear. 

ISP Costs - Synchronous Gigabit Internet $150 per month.
VPS Costs -  2 VPS Servers @ $50 each per month.  
Hosting Fees - $25 Per Month.
Zoom - $200 per year .
OV Wildcard SSL Cert - $200 per year. 

| 1b. | Backend  |  Our app is fully dockerized and ready for rapid stand alone deployment.   Each major function is in its own container that can be managed separately.  Containers include the ipfs daemon, a separate container for IPFS Cluster nodes, Postgres, Database Listener/Message Broker, Vechain node, and the web app itself running Django and Nginx.  
| 1c. | WebApp   |  Users will be able to login and access the webapp. The app itself focuses on showing the activity of data being exchanged.   Users are able to see 
messages queued, sent, and received. Users are able to manage client relationships as well as send manual messages.   
| 1d. | Website  |  Our primary website is built and launched showing an explanation of our app, key details, and offers users the ability to request a demo. Software is online and we are ready to provide a demo.  


#### Milestone 2  —  On-Prem Data Broker, Initial Data Scripts, ERP Integration  

| 2a. | GraphQL API Gateway | Create GraphQL based data gateway alllowing for the bidrectional exchange of key data via GraphQL API.  

| 2b. | On-Prem Data Broker | Middelware designed to manage the exchange of data between on-prem ERP database and the webapp.  This app will reside on 
the customer network and can be securely connected to the webapp's graphql interface to exchange data.   Data will be sent and received based on pre-defined and validated scripts.  This app, for this milestone, will connect initially to an oracle database.  Additional database types will be added in the future. 

| 2c. | Integration Scripts | The first integration scripts will be generated for this milestone.  These scripts will manage the import, export, and translation of data.  Initial operations to be covered include Shipping Notifications, Shipping Detail, Work Order Update, Sales Delivery Date Change, Payment Generated Alert. 

| 2d. |  ERP Integration | The initial integrations will be for Oracle databases as well as connecting via the ODBC interface. This connection will allow for connecting the specified server and database and will facilitate the data IO operations.   

| 2e. |  Test Suite   | -  We will develop a test suite to enable testing of all key functions including ERP database connections, sending and receiving transactions, and encryption/decryption processes.  



#### Milestone 3  —  Smart Contract 
| 3. | Smart Contracts | This milestone focuses on the creation and impplementation of the smart contract that will drive the service.

| 3a. | Access Controls |  Control for VIP191 Fee Delegation vs Payment by Sender

| 3b. | Public Directory |  Public  Authenticated Wallet Address Listing Via VIP192  

| 3c. | IPFS Access Control | Keyshare for IPFS 

| 3d. | Contractor Commissions | Process to drive payment of contractor commissions on transactions
 


#### Milestone 4  —  I/O Script & ERP Integration Expansion, Documentation 
| 4a. | Data Import Export Scripts - We will expand the range of standard data scripts that we will support for each ERP integration.   

| 4b. | Additional ERP Integrations - We will expand our connection options to include a Microsoft SQL Server integration 
and a Salesforce Lightning integration.  All standard data import export scripts will be built for each specific ERP system to 
simplify and accelerate integration.  

| 4c. | Documentation | We will generate a full suite of documentation that details the process for setup, configuration, integration, and use of the software. We also intend to generate Youtube videos showing a walk through of the software and a demonstration of key processes.   

| 4d. | Transactional Support   |  We request the sponsoring of 100,000 VTHO.  These tokens will be used specifically for on-chain transactions by the webapp. 
With this support it will enable us to offer new customers an initial amount of free transactions to enable experience with the software and hopefully increase traction at no cost to the customer. 


#### Community engagement
Medium Article - We will produce an article and publish it in Medium describing our app and its development as part of the program.   
Discord Server - We will be setting up and operating a discord server for hosting discussion of the app, its functionality, and support.  
Community Events - We are active in the blockchain and startup communities in the greater Los Angeles/San Diego region.  We intend to openly 
discuss our app at various networking events.    
LinkedIN -   We will be using LinkedIN to reach out to our existing contact networks to share this tool and ignite interest. 
Tradeshows - As we gain traction we are prepared to attend and present at industry tradeshows for our targeted verticals.   


## Future Plans
The intention of our team is to use this grant to complete the buildout of our project and begin implementation with existing clients.  With a small amount of traction we will add new features, increase the number of ERP integrations and begin building out a network of integrators who will bring online more companies using this tool.  Our initial focus will be on manufacturing and service companies as well as companies within the aftermarket automotive parts vertical.  We also will look for opportunities to integrate with the  pharmaceutical & medical device verticals to expand the network into those verticals as well via partnerships with other software consultancies. 

We view our tool as a data gateway for helping companies access new Web3/Defi technologies using their existing business management solutions.  We see many opportunties for expansion of managing the exchange of data between companies. We will expand our standard data exchange offerings in areas of transactional data, audit controls, accounting/financial controls, and digital certification validation.  We also intend for this company to be global in scale by serving and supporting B2B relationships overseas and across borders.  

Long term client expansion plans are focused on growth via client word of mouth, native integration with ERP software providers, and developing a network of IT firms, software consultants, and integrators who will be compensated for all transactions their integrations generate.   

Always creating more valuable transactions.  


## Additional Information 

Our app is entirely self funded and so far represents several years of discussion with clients, planning, design, and development work 
to find a way to better meet our clients needs at lower price point than incumbent players utilizing other technologies.  Vechain's platform 
combined with other technologies meet those requirements.  This is our first grant application.  Our sincere goal here is to build this app 
as a bridge to blockchain technologies from existing on-prem and cloud technologies.  

