[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8553919&assignment_repo_type=AssignmentRepo)
# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. See the [instructions](instructions.md) for more detail.

## Team members

[Robert Chen](https://github.com/RobertChenYF)\
[Sarah Al-Towaity](https://github.com/sarah-altowaity1)\
[Brian Lee](https://github.com/shl622)

## Ideation
<details>
<summary>Pharmacy chat app</summary>
<br>
Potential Stakeholders: retail pharmaceutical company, retail pharmacists <br/>
Potential End-user: retail pharmacy customers, pharmacists<br/>
Problem attempting to solve: The demand of customers to be connected to local pharmacies via phone is too high for the number of resources available at a pharmacy. The program aims to solve this problem by allowing customers and pharmacists to communicate via chat, whether it is live (on-demand) or a mail-like system where the customer posts questions and checks in later for an answer.
</details>

<details>
<summary>NYC Street Parking app </summary>
<br>
Potential Stakeholders: entreprenuers, NYC government <br/>
Potential End-user: NYC drivers <br/>
Problem attempting to solve: The hassle of confirming the parking restriction per street as sometimes the signs are tilted or too far to confirm. If one can access these restrictions via a mobile app that provides location service, it would help drivers in NYC to validate nearest parking spots.
</details>

<details>
<summary>Renting Platform app</summary>
<br>
Potential Stakeholders: entreprenuers, companies who are willing to rent (instead of sell) their products <br/>
Potential End-users: users with items they own that are in good condition but barely use, and users who are in need for such items for a temporary time period <br/>
Problem attempting to solve: Match those who are in need of an item for  a limited period of time with those who own these items and want to rent it out. 
</details>

<details>
<summary>Buy&Sell Used Items app</summary>
<br>
Potential Stakeholders: entreprenuers, institutions who approve of model </br>
Potential End-Users: college students </br>
Problem attempting to solve: hassle of shipping and packaging in existing models, the risk in having to deal with a stranger(non-verified) online, filtering and targeting items in specific needs for students 
</details>


## Stakeholders

### Ashton, student at NYU Stern
**Goals/Needs**\
<span>1. </span> Reducing counterparty risk for both ends of the P2P trade by having users verify themselves in the system as enrolled college students.<br/>
<span>2. </span> Establishing a payment transfer system whereby the funds would go from the buyer to an Escrow account of G-SIB* to the seller once this verification is completed.<br/>
<span>3. </span> Removing the overhead imposed by shipping and delivery logistics by having both the buying and the selling party to meet in-person to complete the trade.<br/>
<span>4. </span> Ensuring that the needs of the seller and the buyer parties remain aligned, especially given that the userbase is limited to the set of people who are verified college enrollees and even further limited to subsets of students from the same institution. <br/>
<span>5. </span> Target institutions with high number of students as these would are more likely to provide the platform with an extensive userbase that can interact with each other, especially since students are only allowed to trade with those who are enrolled to the same institution.<br/>


**Problems/Frusturations**\
<span>1. </span> Most current virtual marketplace platforms suffer from counterparty risk**. For example, Facebook marketplace comes short on this virtue as the user has to rely on reputation or instincts to evaluate whether the opposite end of the trade is trustworthy. As someone who wants to build a marketplace platform, this risk stands as a problem that needs to be handled.<br/>
<span>2. </span> Logistics related to shipping and packing as well as litigations related to shipments are expensive and require a ton of oversight. <br/>
<span>3. </span> Many existing used item markets deal with a broad range of listings from a broad range of users, leading to a wide range of items but requires time and effort to tailor them to the needs of a specific userbase.
<br/>
<span>4. </span> For any such platform to succeed, a challenge to be overcome is securing a large enough userbase to appreciate the value of the platform, as per the networking effect***.<br/>

*global systemically important banks </br>
**the probability that the other party in an investment, credit, or trading transaction may not fulfill its part of the deal and may default on the contractual obligations. </br>
***As the userbase of an app increases, the app’s value increases exponentially. </br>

## Product Vision Statement

A mobile application where college students can buy or sell anything from their fellow peers locally without dealing with packing or shipping concerns.

## User Requirements

<span>1.</span> As a college student, I want to view the listed items for sale on the home page, so that I can see if there is an item I would like to purchase. <br/>
<span>2.</span> As a user, I want to get verified using my college email, so that I can start buying on the platform.<br/>
<span>3.</span> As a user, I want to get verified using my college email, so that I can start selling on the platform.<br/>
<span>4.</span> As a buyer, I would like to see a seller’s reviews, so I can verify the seller’s credibility.<br/>
<span>5.</span> As a seller, I want to choose my own price, so that I can sell my item at a desired price.<br/>
<span>6.</span> As a buyer, I want to chat with the seller, so that I can possibly bargain on the price. <br/>
<span>7.</span> As a buyer, I would like to search for a specific product, so that I can compare prices and/or sellers and choose the best bargain for me.<br/>
<span>8.</span> As a seller, I want to chat with the buyer, so that I can arrange a meeting place to trade the item in-person.<br/>
<span>9.</span> As a buyer, I want to add my payment information so that I have the buying power for the desired item.<br/>
<span>10.</span> As a seller, I want to link my bank account to my platform profile so that I can transfer funds after a successful transaction.<br/>
<span>11.</span> As a buyer, I would like to include items to my wish list, so that I can try to get them later on.<br/>
<span>12.</span> As a buyer, I would like to chat with the seller, so that they can send me a request to buy after discussing details of the purchase (arranging meetups, price negotiation,etc).<br/>
<span>13.</span> As a seller, I would like to be able to send the buyer a request to buy after making arrangements for a meetup, so that they can purchase my product.<br/>

## Activity Diagrams

![verify activity disgram](/Activity%20Diagram/User%20verifiy%20activity%20diagram.png)
As a user, I want to get verified using my college email, so that I can start buying on the platform. 

![buy item diagram](Activity%20Diagram/User%20buy%20activity%20diagram.jpeg)
As a buyer, I would like to chat with the seller, so that they can send me a request to buy after discussing details of the purchase (arranging meetups, price negotiation,etc).

## Clickable Prototype

View clickable prototype [here.](https://www.figma.com/proto/Jn5YKRq0i4uEjWCtRfaL7L/Wireframe-ver1?node-id=3%3A11&scaling=scale-down&page-id=0%3A1&starting-point-node-id=3%3A11&show-proto-sidebar=1)