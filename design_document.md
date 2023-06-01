# Everneat Design Document

## Instructions



## *Custom Shipping* Design

## 1. Problem Statement
  In our Shopify store, we currently have a customer segmentation system in place using customer tags. These tags help us categorize and identify specific groups of customers based on their characteristics or behaviors. However, we have identified a need for a custom shipment process tailored specifically to customers with certain tags.

  Currently, our default shipment process treats all customers equally, without considering the unique requirements or preferences of customers with specific tags. This generic approach to shipping may result in suboptimal customer experiences and operational inefficiencies. Therefore, we need to implement a custom shipment solution that addresses the following challenges:

    1. Customer Segmentation: We need to identify customers with specific tags and create a distinct shipment process for them. These tags could represent different customer types, such as wholesale customers, VIP customers, or customers from a specific geographic region.

    2. Shipping Rules and Logic: Implementing custom shipments for specific customer tags involves defining and configuring appropriate shipping rules and logic. We need to determine how these customers will be assigned to the custom shipment process and how their shipping options and costs will be calculated.
    
    3. Scalability and Flexibility: As our business grows and evolves, we should be able to easily modify and expand our custom shipment solution to accommodate new customer tags or changing requirements. The solution should be scalable, flexible, and future-proof.



## 3. Use Cases


U1. As Admin, I want to see Add custom , when I provide Email as Username and password

U2.	As Customer, I want to Create a message SP


## 4. Project Scope

*Clarify which parts of the problem you intend to solve. It helps reviewers know
what questions to ask to make sure you are solving for what you say and stops
discussions from getting sidetracked by aspects you do not intend to handle in
your design.*
- Online presence of skilled individual as service provider
- Rate and write review about service rendered by SP for other customer's reference.
- Service quotation for customer's budgeting reference.
- Availability of Service Provider
- appointment booking conflicts.
- separate means of communication.

### 4.1. In Scope

*Which parts of the problem defined in Sections 1 and 3 will you solve with this
design?*
- Creating, retrieving and updating user account
- Creating, retrieving and updating Service
- Creating, updating and canceling appointment
- Adding to and retrieve saved appointment to booking
- Creating, sending and retrieving Message
- - Creating, sending and retrieving Reviews

### 4.2. Out of Scope

*Based on your problem description in Sections 1 and 3, are there any aspects
you are not planning to solve? Do potential expansions or related problems occur
to you that you want to explicitly say you are not worrying about now? Feel free
to put anything here that you think your team can't accomplish in the unit, but
would love to do with more time.*
- Admin Page
- Billing
- Gift Cards and Referal bonus
- Service provider as Group/Company
- Ability to manage personnel

# 5. Proposed Architecture Overview

*Describe broadly how you are proposing to solve for the requirements you
described in Section 3.*

*This may include class diagram(s) showing what components you are planning to
build.*
#### [Admin Class Diagram](ClassDiagrams/Custom ShippingAdminUCD.puml)
#### [Customer Class Diagram](ClassDiagrams/Custom ShippingCustomerUCD.puml)
#### [Service Provider Class Diagram](ClassDiagrams/Custom ShippingServiceProviderUCD.puml)

*You should argue why this architecture (organization of components) is
reasonable. That is, why it represents a good data flow and a good separation of
concerns. Where applicable, argue why this architecture satisfies the stated
requirements.*


# 8. Pages

*Include mock-ups of the web pages you expect to build. These can be as
sophisticated as mockups/wireframes using drawing software, or as simple as
hand-drawn pictures that represent the key customer-facing components of the
pages. It should be clear what the interactions will be on the page, especially
where customers enter and submit data. You may want to accompany the mockups
with some description of behaviors of the page (e.g. “When customer submits the
submit-dog-photo button, the customer is sent to the doggie detail page”)*

![](images/design_document/16.png)
