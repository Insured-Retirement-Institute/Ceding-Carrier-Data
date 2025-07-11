# Ceding Carrier Data
Auto populating ceding carrier data while completing a replacement during the order entry process. 

Please refer to the [style guide](https://github.com/Insured-Retirement-Institute/Style-Guide) for technical governance of standards, data dictionary, and the code of conduct.

## Business Case
Executive Summary: 

Ceding Carrier Contract Information to populate in the Order Entry (OE) platforms when it is an Exchange/Transfer.  

Problem: 

*Problem*. Causing multiple issues with advisors selecting the wrong location of ceding carrier in YellowPages, calling carrier and sitting on phone for 20-30 mins, putting in wrong info on the ceding contract, multiple NIGOs and Supervision Inquires tying back to this screen on OE platforms.  

 

2 Paths to Solve: 

 

When BD is already broker of record on the contract – should be less of an issue to get the data from DTCC (For JPMC in 2024 this was the case for 75% of our exchanges/transfers) DTCC plans to look for policy number and validates: requesting broker dealer (not the specific advisor) and carrier. Do we need to validate anything else? (Athene, Global, Nationwide and NYL – nothing else) 

When BD is NOT already broker of record on the contract. Understanding from the client they are planning to surrender the contract and move to a new one. 

Objectives and Key Results 

  Objective: Prepopulate the required data points the client/advisor need. 
Key Result:  

 - Time spent on OE platform – if we can drill down to that specific screen 

 - Carrier call centers taking calls on ceding carrier contracts 

 - NIGO numbers that stem back to the OE platform page (Zinnia – Additional Payments Screen) 

 - Supervision Inquires that stem from that page 

 - Right/Wrong selections of addresses on YellowPages 

## User Stories, personna - supporting documents for the business case
Use Case 1: Remove the pain points for the user of the page for all the reasons stated above.  

User Story 1: As a financial advisor and client – I want this page in the UI to be prepopulated for me so I don’t have to call or guess. I can just validate and move on with the new sale.  
<img width="1236" height="705" alt="image" src="https://github.com/user-attachments/assets/a080f88d-f709-4981-bfc0-3fc0df25fa0e" />

## Business Owners 
- Distributor Business Owner: JP Morgan Chase - Leland Snyder
- Solution Provider Business Owner: DTCC - Jeanann Smith; Zinnia - Saul Herrera 

## How to engage, contribute, and give feedback
- These working groups are occuring on Tuesdays at 10am Eastern Time
- Please contact the business owners or IRI (hpikus@irionline.org) to get added to the working group discussions. 

## Change subsmissions and reporting issues and bugs

Security issues and bugs should be reported directly to Katherine Dease kdease@irionline.org. Issues and bugs can be reported directly within the issues tab of a repository. Change requests should follow the standards governance workflow outlined on the [main page](https://github.com/Insured-Retirement-Institute).

## Code of conduct

See [style guide](https://github.com/Insured-Retirement-Institute/Style-Guide)
