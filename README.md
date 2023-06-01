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

  U1. As Admin, I want to see Add custom Shipping Logic button
  U2.	As Admin, I want to Create a shipping rate for a specific customer tag.
  U3. As 'b2b' tagged customer, I want to see all shipping rates including custom shipping rates for b2b;
  u4. As no specific tagged customer, I want to show all shipping rates except for b2b shipping rates;


## 4. Project Scope

-custom shipping rates

### 4.1. In Scope
- Showing b2b custom shipping rates for b2b tagged customers
- Hide b2b custom shipping rates for on specific tagged customers(regular customer)

### 4.2. Out of Scope

- Discount Line
- Product Line
- Cart Line

<-- Below is for developer to answer-->

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


