# Fawry-like Payment System

## Introduction

- In this project, you will design and implement a non-trivial software system. You will practice the concepts you learned during the course.
- The project will consist of at least 2 phases.
- In each phase, we will focus on designing and implementing some requirements.
- The project must be developed in the Java programming language using the "Eclipse IDE for Java" specifically.
- The deliverables include:
  - Proposed class diagram
  - Sequence diagrams for the most complex scenarios (8 in total)
  - Git repository for the developed source code project.

## Project Logistics

- Team Size: 3-4 members.

## Project Overview

### Description

In this project, you will build a system similar to Fawry that allows users to pay for different services. The initial services include:

a. Mobile recharge services.
   - Vodafone
   - Etisalat
   - Orange
   - We

b. Internet Payment services.
   - Vodafone
   - Etisalat
   - Orange
   - We

c. Landline services.
   - Monthly receipt
   - Quarter receipt

d. Donations.
   - Cancer Hospital
   - Schools
   - NGOs (Non-profitable organizations)

### Requirements

#### User

1. The user should be able to sign in to the system using their email and password to access system functionalities.
2. The user can sign up for the system by providing a username, email, and password. The system should check if the username or email is already registered. If not, the signup process should complete successfully; otherwise, an error should be shown.
3. The user can search for any service in the system by typing the service name, and the system will return all matching services.
4. The user can pay for any service in the system, with payment options including credit card and wallet. If the service accepts cash on delivery, this option should also be available.
5. The user can request a refund for any completed transaction, which will be sent to the admin for approval.
6. Users have a wallet balance, and they can add funds to it via credit card.
7. Users can check for any available discounts for services in the system, which can be added by the admin.

#### Admin

1. The admin can add new service providers to the system, defining a form to be filled by the user and a handler for this form. For example, Vodafone Cash provider consists of a form (Mobile number, amount) and a handler for this form.
2. The admin can add discounts to the system, including overall discounts (e.g., first transaction discount) and specific discounts for services.
3. The admin can view user transactions, including payment transactions, wallet top-ups, and refunds.
4. The admin can list refund requests, accept or reject them, and process refund transactions accordingly.
