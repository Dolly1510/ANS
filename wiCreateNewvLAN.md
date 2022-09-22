# Adding new VLAN in ANS - MAR CLY

Table of Contents
- [Changelog](#Changelog)
- [Introduction](#Introduction)
- [Purpose](#Purpose)
- [Scope](#Scope)
- [Prerequisites](#Prerequisites)
- [Stages For Adding VLAN](#Stages-For-Adding-Puppet-Roles)
- [Add the VLAN in ANS-MAR CLY](#Add-the-VLAN-in-ANS-MAR-CLY)

# Changelog
  
| Version | Date       | Description              | Author       |
| ------- | ---------- | ------------------------ | --------------- |
|  0.1    | 21/09/2022 |   Add VLAN in ANS - MAR CLY           | Dolly Vemula |

# Introduction

## Purpose

The purpose of this document is to describe steps that should be performed to Add new VLAN in ANS - MAR and CLY.

## Scope

The scope of this document covers the following:

  - Updating/Adding New VLAN in the ANS - MAR CLY.

## Prerequisites
    
  -  Access to the both ANS - MAR , CLY in VRA Environment.
     
# Steps for Adding VLAN in ANS - MAR CLY

To Update/Add New VLAN we need to follow 3 main steps:

   - Step1:  We need to check the Required VLAN is Available in the Network Profile and check the tags.

   - Step2: Need to Update\add the VLAN in Cloud Assembly.

   - Step3: Verify in the service broker weather the VLAN is added or not.
 
# Add the VLAN in ANS-MAR CLY

## Step 1

## Updating/add VLAN Process in ANS - MAR CLY

  ## 1.1 Sign in VRA Environment
 
    First log on to VRA.

      - Then click the cloud assembly.

![Figure 1](Pic1.png)

  ## 1.3 Verify VLAN is in the Network profile

     -click on the Infrastructure.

![Figure 2](Pic2.png)

  ## 1.3 Verify the Tags are Updated

     - Click on the Network Profile and search for the Respected VLAN is available or not.
     
     - If the VLAN is not available then verify and contact with respected team member to make it available here.

![Figure 3](Pic3.png)

Lets consider the following VLAN as Example:

The following VLAN name is - mar01lsw10_VMW_PCAANS_SRV 

we choose a capability tag according to the VLAN name matching. 

![Figure 12](Pic12.png)

 ## 1.4 Check network tags  
     
click on network
     
![Figure 13](Pic13.png)

Now match with the VLAN name and choose the Network we want.

![Figure 14](Pic15.png)

## 1.5 Add Network Tag if required

    - If the Network tag is not available with name matching in the Network we need to add the Network.
    
![Figure 15](Pic16.PNG)

## Step 2

## Update VLAN in the Cloud Assembly

   ## 2.1 Select required Template

     - Click on the Design and select/search for the respected Blueprint.

![Figure 4](Pic4.png)
   
   ## 2.2 Add required VLAN  in the Template

     - Now need to add the VLAN in the Blueprint.

![Figure 5](Pic5.png)
 
   ## 2.3 Version the Blueprint.

    - click on the version button in the blueprint.
   
![Figure 6](Pic6.png)
   
## step 3

## Verification in Service Broker

  ## 3.1 In Service Broker

      - Click on the service broker.

![Figure 7](Pic7.png)
         
  ## 3.2 Project in Content&Policies

     - In service broker click on the content&policies and then select content sources.

![Figure 8](Pic14.PNG)
         
  ## 3.3 Validation in content&Policies

     - Click on the validate and then save & import.

![Figure 9](Pic9.png)

  ## 3.4 Select Catalog 

     - In the service broker under catalog search/select the respected catalog.

![Figure 10](Pic10.png)

  ## 3.5 Verify VLAN in the Catalog

     - Verify the newly added VLAN in the VLAN dropdown.

![Figure 11](Pic11.png)


