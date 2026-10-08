# Home Credit Loan Against Property Voice Agent

## Project Overview

This project is a Voice AI Agent developed for the Home Credit Loan Against Property (LAP) assignment.

The agent acts as the first point of contact for an existing Home Credit customer. It informs the customer about a pre-approved Loan Against Property offer of up to seventy-five lakh rupees and performs a preliminary eligibility check through a natural voice conversation.

The agent does not approve loans, guarantee approval, or quote interest rates. If the customer meets the basic eligibility criteria, a senior loan expert will contact the customer for the next steps.

## Platform

Retell AI

## Main Objectives

The voice agent is designed to:
- Inform customers about the LAP offer.
- Conduct a preliminary eligibility check.
- Ask one question at a time.
- Remember information already provided by the customer.
- Skip questions that have already been answered.
- Handle answers given out of order.
- Detect disqualifying conditions immediately.
- Handle existing loans and loan-transfer situations.
- Handle callback requests.
- Support English and Hindi.
- Avoid collecting sensitive information.
- End every conversation with an appropriate outcome.

## Eligibility Information Collected

1. Property type
2. Ownership status
3. Availability of original property documents
4. Required loan amount
5. Occupation
6. Income mode
7. Property market value
8. Desired loan tenure

## Main Eligibility Rules

- Residential, commercial, and industrial properties are eligible.
- Agricultural properties are not eligible.
- The property can be solely or jointly owned.
- Original property documents must be available.
- Income must be received through a bank account.
- The maximum loan amount for this offer is seventy-five lakh rupees.
- Loan tenure must be between 3 and 15 years.
- Existing loans on the same property trigger the loan-transfer flow.
- The agent never quotes interest rates.
- The agent never guarantees loan approval.
- The agent does not request OTP, PIN, CVV, passwords, Aadhaar, PAN, bank account numbers, or exact property addresses.

## Scenarios Tested

1. Happy Path
2. Busy Customer
3. Agricultural Property
4. Cash Income
5. Original Documents Not Available
6. 20-Year Tenure
7. Existing Loan
8. Loan Amount of ₹1 Crore
9. Answers Given Out of Order
10. Hindi Language Call

## Testing

The agent was tested for:
- Natural conversation
- One-question-at-a-time behavior
- Conversation memory
- Slot tracking
- Out-of-order answers
- Disqualification handling
- Existing-loan transfer handling
- Callback handling
- Loan amount limit handling
- Hindi language support
- Correct call termination
- Avoiding sensitive information collection

## Deliverables

- Retell AI Voice Agent
- Complete System Prompt
- Testing Scenarios
- Call Recordings
- Call Transcripts
- Published Voice Agent
- Screen Recording Demonstration

## Result

The required test scenarios were completed and the voice agent conversations, transcripts, and recordings were reviewed.
