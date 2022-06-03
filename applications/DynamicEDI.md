# VeChain General Grant Application 

## Project Overview 

- Project: GetDynamic
- Team Name: AerodynamicData 
- USDT Payment Address: 0x8D4AA616E759058A9aD5cD4F43F4CbD23A7A6Baf
 


### Overview

GetDynamic is a blockchain EDI(Electronic Data Interchange) messaging system focused on automating data exchange between business partners.  The app will integrate with existing on-prem and cloud based ERP (Enterprice Resource Planning) database platforms, facilitating pre-defined and custom scripts to automatically send and receive data. The integration tool is designed to quickly and easily allow any database to be connected for both sending and receiving.  Standard EDI formats will be supported but are not required to be followed.  

This project was inspired by Ryan Realivasquez's 15 years of experience as an ERP consultant in the aerospace industry. Many companies have the same issues with data, yet do not have any easy way of exchanging the data they need securely.  Most companies are still exchanging small amounts of data via phone and email or are using legacy centralized systems at great cost.  Existing EDI services have too high a cost of entry for small to medium sized businesses to take advantage of such tools. GetDynamic significantly reduces that transcation cost while still providing a private and secure service, therefore this specalised automation is available to a wider array of companies.  Users will have a choice to pay for transactions either from their own wallet directly or via subscription managed using VIP191.  No subscription or payment is required to receive transactions.    


### Project Details

Our project is primarily based on Python, Django and Postgres.  Other technologies being used include Go, C#, Docker, Javascript,  
VMWare, IPFS, Truenas, and Cloudflare. 

 
Mockups/designs of UI components:
 
- Login Page
![login-page](https://user-images.githubusercontent.com/11070873/168932198-c7ab7301-a457-403b-9293-2995e348d78d.png)
 
- Main Dashboard Page 
![Dashboard](https://user-images.githubusercontent.com/90410142/171931601-2adec06c-56b0-4c90-bab4-683640ebfa20.png)

- Adding A Company / Companies Page
![companies-page](https://user-images.githubusercontent.com/11070873/168932639-db1b128a-60a1-415e-8d41-34a76a8584c5.png)

- Company List
![company-list](https://user-images.githubusercontent.com/11070873/168932731-1b1f08eb-4269-40b1-ad2e-36cbc2b49803.png)

- Send New Message
 ![send-new-message](https://user-images.githubusercontent.com/11070873/168932804-7240a274-6db7-4d64-8082-cb15bf0deeee.png)

- System Configuration
![system-config](https://user-images.githubusercontent.com/11070873/168932902-4bf0df7c-4b5e-4601-b1e8-f018318260f7.png)

- Add Transaction Type
![add-trans-type](https://user-images.githubusercontent.com/11070873/168932979-6dde98f1-40c8-44da-91d9-6647f5cdf348.png)

- API specifications of core functionality:
 An API will be built and published that integrates all core functionality (Sending and Receiving Transactions, Key Exchange, History Download, etc) as part of Milestone2.  
 

### Ecosystem Fit
Within Vechain no comparable projects are apparent.  On other chains we have found messaging systems but have not found any that focus on connecting to ERP systems for data exchange.  Companies providing legacy EDI systems include TrueCommerce, Seeburger, and IBM Sterling.  Our app fits well within the Vechain ecosystem;it will provide an on-ramp for companies to leverage existing infrastructure in accessing and taking advantage of modern distributed ledger technology. 


## Team 

### Team members & Contributors
- Ryan Realivasquez (Founder, Full stack Development) 
- Matt Haydon (Cofounder, Web Development, Marketing) 
- Genaro Coronel (Full Stack Development) 
- Oleg Tropinin (Full Stack Development) 

### Team Website

- https://getdynamic.app

### Team's experience

Please describe the team's relevant experience. If the project involves development work, then we'd appreciated it if you can single out a few interesting codes commits made by team members on their past projects. 

Ryan Realivasquez is the primary founder of GetDynamic. As a consultant in the aerospace industry he brings over 15 years excelling in implementing and supporting ERP systems. Through this experience he identified the need for a lower cost and more widely available system for exchanging data between companies.   Utilizing the stengths of Blockchain technology he developed a simplified EDI system that addresses the needs of his clients as well as the industry overall. Getdynamic strengthens and improves upon existing EDI systems by focusing on three things:  Privacy.  Simplicity. Cost.  Ryan launched development of the app, has researched and defined the infrastructure technologies to be used, defined the features and product roadmap, and has self funded the engagement of professional developers to complete initial development. 

Matt Haydon is a cofounder of GetDynamic.  He has past experience launching several small businesses and is an influencer within the blockchain space operating successful social media communities.   Matt is also contributing to development of our app by focusing on designing and building the User Experience(UX) in our interfaces as well as planning, and when it is time executing, our web marketing plan.  

Genaro Coronel is our principal developer. He has added several major features to the infrastructure of our app and will be our primary smart contract seveloper as well. He is responsible for coding our IPFS-Cluster storage backend, Dockerizing the infrastructure, and connecting the app to the Vechain network.  

Oleg Tropinin has contributed to early development efforts and will be rejoining us for future development.  He has been responsible for our initial Vechain integration, web app infrastructure setup, and django configuration.  
 


### Team Code Repos
Will provide via DM.

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
| Full-time equivalent (FTE) | 2 | 4 | 2 | 2 | 2 |
| Cost (up to $ 30,000) | $ 7,500 | $ 10,000 | $ 7,500 | $5,000| $ 30,000|

#### Milestone 1 — Infrastructure, Backend, WebApp,  Website  

This first milestone represents work in-progress and tasks completed.   We ask the foundation to please review our submitted work, validate completion of this 1st milestone, and deliver payment upon validation.   This will enable us to launch and move forward on completion of the remaining milestones. 

| 1a. | Infrastructure  | Our goal is to secure funding for the first year of infrastructure service costs.  This covers a primary and backup VPS service each operating Vechain testnet and mainnet nodes, on-prem and cloud storage services for the network, data backups, and monitoring. Internal production and test network topology is configured for security with current generation enterprise quality gear. 
- ISP Costs - Synchronous Gigabit Internet $150 per month.
- VPS Costs -  2 VPS Servers @ $50 each per month.  
- Hosting Fees - $50 Per Month.
- Zoom - $200 per year .
- OV Wildcard SSL Cert - $200 per year. 

| 1b. | Backend  |  Our app is fully dockerized and ready for rapid stand alone deployment.   Each major function is in its own container that can be managed separately.  Containers include the ipfs daemon, a separate container for IPFS Cluster nodes, Postgres, Database Listener/Message Broker, Vechain node, and the web app itself running Django and Nginx.   Repository documentation contains all details for launching the app however it simply can be built using 1. sudo bash build_project.sh     and 2. docker-compose up -d  .  These two commands ran from the local repository folder will result in a functioning app ready for an account to be created and log in.  
| 1c. | WebApp   |  Once containers are built and services started under milestone 1b, users are be able to login and access the webapp. The app itself focuses on showing the activity of data being exchanged, managing client relationships for purposes of data exchange, as well as integration with customer ERP database. 
Users will be able to send a manual message to validate functionality and on-chain transactions.
| 1d. | Website  |  Our primary website is currently active showing an explanation of our app, key details, and offers users the ability to request a demo. Software is online and we are ready to provide a demo.  Instructions to access demo are also provided in private repository. 


#### Milestone 2  —  API,  On-Prem Data Broker, Initial Data Scripts, Test Suite 

| 2a. | OpenAPI API Gateway | Create OpenAPI  based api for performing all key functions.   API will be made available on RapidAPI. 
- Send New Transaction 
- Receive Transactions 
- New Exchange Request 
- IPFS Keyshare 
- History Download 
- Company Match 

| 2b. | On-Prem Data Broker | Middelware designed to manage the exchange of data between on-prem ERP database and the webapp.  This app will reside on 
the customer network and can be securely connected to the webapp's API interface to exchange data.   Data will be sent and received based on pre-defined and validated scripts.  This app, for this milestone, will connect initially to an oracle database.  Additional database types will be added in the future. 

| 2c. | Integration Scripts | The first integration scripts will be generated for this milestone.  These scripts will manage the import, export, and translation of data.  Initial operations to be covered include Shipping Notifications, Shipping Detail, Work Order Update, Sales Delivery Date Change, Payment Generated Alert. 

| 2d. |  Test Suite   | -  We will develop a test suite to enable testing of all key functions including ERP database connections, sending and receiving transactions, and encryption/decryption processes.  



#### Milestone 3  —  Smart Contract 
| 3. | Smart Contracts | This milestone focuses on the creation and impplementation of the smart contract that will drive the service.

| 3a. | Access Controls |  Control for VIP191 Fee Delegation vs Payment by Sender

| 3b. | Public Directory |  Public  Authenticated Wallet Address Listing - This will be about creating an authenticated listing of public addresses 
that companies can be reached at for purposes of this app.   This public address is only used for two purposes:  To validate the company and initiate contact.  

| 3c. | IPFS Access Control | Keyshare for IPFS - As new client relationships are formed clients have the option of using a shared IPFS swarm that all users subscribe to or utilizing a private IPFS swarm shared only between two companies.   The key to access seach network share will be encrypted and exchanged triggering a new swarm to be created using the shared key.  

| 3d. | Integrator Commissions | Process to drive payment of commissions on transactions.  As transactions are generated an integrator ID code can be transmitted to indicate responsibility for generating these transactions.  A % of fees is then directed to this integrator on a periodic basis. 
 


#### Milestone 4  —  I/O Script & ERP Integration Expansion, Documentation 
| 4a. | Data Import Export Scripts - We will expand the range of standard data scripts that we will support for each ERP integration.   

| 4b. | Additional ERP Integrations - We will expand our connection options to include a Microsoft SQL Server integration 
and a Salesforce Lightning integration.  Standard data import export scripts will be built for each specific ERP system to 
simplify and accelerate client integration.  

| 4c. | Documentation | We will generate a full suite of documentation that details the process for setup, configuration, integration, and use of the software. Youtube videos will be created showing a walk through of the software and demonstration of key processes. Specifically, we will provide detailed instructions on how to create new import and export scripts to meet the user's specific needs.     

| 4d. | Transactional Support   |  We request the sponsoring of 100,000 VTHO.  These tokens will be used specifically for on-chain transactions by the webapp. 
With this support it will enable us to offer new customers an initial amount of free transactions to enable experience with the software and hopefully increase 
traction at no cost to the customer. 


#### Community engagement
Medium Article - We will produce an article and publish it in Medium describing our app and its development as part of the program.   
Discord Server - A discord server has already been setup at https://discord.gg/85qvDyrnZu.  This will be a place users can discuss the app, request support, and see feature announcements.  
Community Events - We are active in the blockchain and startup communities in the greater Los Angeles/San Diego region.  We intend to openly discuss our app at various networking events and invite people to test it and consider building integrations for it.    
LinkedIN -   We will be using LinkedIN to reach out to our existing contact networks to share this tool and ignite interest. 
Tradeshows - As we gain traction we are prepared to attend and present at industry tradeshows for our targeted verticals.   


## Future Plans
The intention of our team is to use this grant to complete the buildout of our project and begin implementation with existing clients.  With a small amount of traction we will add new features, increase the number of ERP integrations and begin recruiting a network of integrators who will bring online more companies using this tool.  Our initial focus will be on manufacturing and service companies within several different markets. We also will look for opportunities to integrate with import-export businesses as well growth via partnerships with other software consultancies. 

We view our tool as a data gateway for helping companies access new Web3/Defi technologies using their existing business management solutions.  We see many opportunties for expansion of managing the exchange of data between companies. We will expand our standard data exchange offerings in areas of transactional data, audit controls, accounting/financial controls, and digital certification validation.  We also intend for this company to be global in scale by serving and supporting B2B relationships across borders and over seas.  

Long term client expansion plans are focused on growth via native integration with ERP software providers, client word of mouth, and developing a network of IT firms, software consultants, and integrators who will be compensated for all transactions their integrations generate.   

Always creating more valuable transactions.  


## Additional Information 

Our app is entirely self funded and represents several years of discussion with clients, planning, design, and development work. Our vision is to find a way to better meet our clients needs at lower price point than incumbent players utilizing other technologies.  Vechain's platform combined with other technologies serve to meet those requirements.  This is our first grant application.  Our sincere goal is to build this app as a bridge to blockchain technologies from existing on-prem and cloud technologies.    

