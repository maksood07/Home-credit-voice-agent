# Home Credit Voice Agent Testing Scenarios

## Overview

The Home Credit Voice Agent was tested using the required scenarios to verify its conversation flow, eligibility logic, callback handling, memory, language support, and call termination behavior.

## 1. Happy Path

agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. This is Rahul. 
agent: I'm priya from Home Credit. I have a special offer for you. Is this a good time to speak for about two minutes?
user: Yes. 
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like to quickly check your eligibility?
user: Yes. 
agent: What kind of property would you like to take the loan against: a house or flat, a shop or office, 
user: Residential property. 
agent: or an industrial property?
agent: Okay. Is the residential property solely in your name or jointly owned?
user: My name only. 
agent: Thanks. Do you have the original property documents available for verification?
user: Yes. 
agent: What amount would you like to borrow?
user: Fifty lakh. 
agent: Just to confirm, you mean fifty lakh rupees, correct?
user: Yes. 
agent: Are you salaried or self-employed?
user: Salary. 
agent: And is your salary credited into your bank account, or received in cash?
user: Yes. 
agent: Does your salary come into your bank account?
user: Yes. 
agent: What is the approximate current market value of the property?
user: One crore. 
agent: Thanks. In how many years would you like to repay the loan?
user: Ten years. 
agent: Thank you, Rahul Sharma. You appear to meet the basic criteria for this offer. A senior loan expert will call you shortly to share the exact interest rates 
agent: and take it forward. Have a great day!

## 2. Busy Customer

Customer says: "I'm busy right now. You can call me after half an hour."

agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. 
agent: I'm priya from Home Credit. I have a special offer for you— is this a good 
user: Yes. 
agent: time to speak for about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like a quick eligibility check?
user: Sorry. Actually, I'm busy now. 
agent: No problem. What time would you prefer I call you back?
user: After thirty minutes. 
agent: I'll call you back at 7:18 AM today. Thank you for your time, Rahul Sharma. Have a great day!
agent: Hello, are you there?
user: Yeah. Yeah. Okay. Thank you. Thank you. 
agent: Thank you, Rahul Sharma. Have a great day!
user: Okay. 

## 3. Agricultural Property

Customer says: "The property is agricultural land."

agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. 
agent: I’m Priya from Home Credit. I have a special offer for you. Is this a good time to 
user: Yes. Yes. 
agent: speak for two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like to quickly check your 
user: Yes. 
agent: eligibility?
agent: What kind of property would you like to take the loan against: residential, commercial, or industrial?
user: The property is agricultural land. 
agent: I’m sorry, but this specific offer isn’t available for agricultural land. Thank you for your time, Rahul Sharma. Have a great 
agent: day.

## 4. Cash Income

Customer says: "I receive most of my income in cash."
agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are speaking with Rahul Sharma. 
agent: I'm priya from Home Credit. Is this a good time to 
user: Yes. Yes. 
agent: speak for about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like to quickly check 
user: Yes. 
agent: your eligibility?
agent: What kind of property would you like to take the loan against: residential, commercial, or industrial?
user: Commercial. 
agent: Is the commercial property solely in your name or 
user: No. 
agent: jointly owned?
user: It's on my name only. 
agent: Do you have the original property documents available for verification?
user: Yeah. Yeah. I have. 
agent: How much would you like to borrow?
user: I want to borrow fifty lakh. 
agent: And are you salaried or self-employed?
user: Self employed. 
agent: Does your income come into your bank account, or do you receive it in cash?
user: I receive most of my incoming cash. 
agent: I’m sorry, but this specific offer requires income to be received through a bank account, so you don’t meet the criteria at this time. Thank you for your time, Rahul Sharma. Have a great 
agent: day.

## 5. Original Documents Not Available

Customer says: "I don't have the original property documents with me."
agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are speaking with Rahul Sharma. 
agent: I’m priya from Home Credit. Is this a good time to speak for 
user: Yes. 
agent: about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like to quickly check 
user: Yes. 
agent: your eligibility?
agent: What kind of property would you like to take the loan against: residential, commercial, or industrial?
user: Distance here. 
agent: Sorry, I didn’t catch that. Is the property residential, commercial, or industrial?
user: Residential. 
agent: Okay. Is the property solely in your name, or jointly owned?
user: And don't have original property documents. 
agent: I’m sorry, but original property documents are needed for this specific offer. Thank you for your time, Rahul Sharma. Have a great 
agent: day!

## 6. 20-Year Tenure

Customer says: "I need a tenure of 20 years."
agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are speaking with Rahul Sharma. 
agent: I'm priya from Home Credit. Is this a good time to speak for about two minutes?
user: Yeah. 
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like to quickly check 
user: Yeah. 
agent: your eligibility?
agent: What kind of property would you like to take the 
user: Residential property. 
agent: Is the residential property solely in your name, or jointly owned?
user: No. It's on my name only. 
agent: Do you have the original property documents available for verification?
user: Yeah. Yeah. I have my original documents. 
agent: How much would you like to borrow?
user: Fifty lakhs. 
agent: Just to confirm, you mean fifty lakh rupees, correct?
user: Yes. 
agent: Are you salaried or self-employed?
user: Salary. 
agent: Does your salary come into your bank account, or do you 
user: Yeah. I my salary 
agent: receive it in cash?
user: comes into my bank account. 
agent: What’s the approximate current market value of the property?
user: One crore. 
agent: How many years would you like to repay 
user: Twenty years. 
agent: the loan over?
agent: I’m sorry, but this offer supports repayment between three and fifteen years, so you don’t meet the criteria for this specific offer at this time. Thank you for your time, Rahul Sharma. Have a great 
agent: day.

## 7. Existing Loan

Customer says: "Yes, I already have an existing home loan."
agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are speaking with Rahul Sharma. 
agent: I'm priya from Home Credit. Is this a good time to 
user: Yes. 
agent: speak for about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like a quick eligibility check?
user: Yes. 
agent: What kind of property would you like to 
user: Residence. 
agent: take the loan against: a house or flat, a shop or office, or an industrial property?
agent: Is 
user: House. 
agent: the house solely in your name, or jointly owned?
user: Yes. It's on my name only. 
agent: Do you have the original property 
user: Yes. 
agent: documents available for verification?
user: Yes. 
agent: How much would you like to borrow?
user: One crore. 
agent: This offer goes up to seventy-five lakh rupees. Would you like to proceed with the maximum amount of seventy-five lakh?
user: Yeah. But I have already have an existing loan. 
agent: Since there’s already a loan on the property, a loan transfer specialist will contact you shortly to help. Thank you for your time, Rahul Sharma. Have a great 
agent: day!
## 8. Loan Amount of ₹1 Crore

Customer says: "I need a loan of one crore."
agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are speaking with Rahul Sharma. 
agent: I'm Priya from Home Credit. Is this a good time to speak for 
user: Yes. 
agent: about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like a quick eligibility check?
user: Yes. 
agent: What type of property would you like to take the loan against: residential, commercial, or industrial?
user: Residential. 
agent: Is the property solely in your name or jointly owned?
user: My it's on my name only. 
agent: Thank you. Do you have the original property documents available for verification?
user: Yes. 
agent: How much would you like to borrow?
user: One crore. 
agent: This offer is available up to seventy-five lakh rupees. Would you like to proceed with the maximum amount of seventy-five lakh?
user: I I want one crew. 
agent: I’m sorry, Rahul Sharma, this offer can’t go beyond seventy-five lakh rupees. Thank you for your time. Have a great 
agent: day!

## 9. Answers Given Out of Order

Customer may say: "The property is my own residential house. It is worth around eighty lakh. I earn seventy thousand per month through my bank account. I need forty lakh for ten years and I have the original documents."

agent: Good evening, am I speaking with Rahul Sharma?
user: Yes. You are talking with Rohit Shar Rohit Sharma? 
agent: I’m calling from Home Credit. Am I speaking with Rahul Sharma?
user: Yes. Yes. 
agent: I’m priya from Home Credit. Is this a good time to speak for 
user: Yes. 
agent: about two minutes?
agent: As a valued Home Credit customer, you have a pre-approved Loan Against Property offer of up to seventy-five lakh rupees. Would you like a quick eligibility check?
user: I want eighty lakh. 
agent: The maximum under this offer is seventy-five lakh rupees. Would you like to proceed with seventy-five lakh?
user: Presidential. 
agent: Do you mean a residential property, 
user: Yes. 
agent: like a house or flat?
user: House. 
agent: Got it, a residential house. Is it solely in your name or jointly owned?
user: My monthly salary is seventy thousand. 
agent: Is your salary credited into your bank account or received in cash?
user: Yes. I already told you I want it. 
agent: I need to know whether your salary comes into your bank account or 
user: Bank account. 
agent: is paid in cash.
agent: Thank you. Are you salaried or self-employed?
user: Salary. 
agent: You’re salaried and your income is credited to your bank account. Are the original property documents available with you?
user: I want around forty lakh. 
agent: Okay, I’ve noted forty lakh rupees. Are the original property documents available with you?
user: Yes. 
agent: Alright, the original documents are available. What’s the approximate current market value of your house?
user: Eighty lakhs. 
agent: Thanks. In how many years would you like to 
user: Ten. 
agent: repay the loan?
agent: You appear to meet the basic criteria for this offer. A senior loan expert will call you shortly with the exact interest rates and next steps. Thank you for your time, Rahul Sharma. Have a great day!
user: Okay. 
agent: Thank you, Rahul Sharma. Have a great day!

## 10. Hindi Language Call

Set the language variable to Hindi.

Example customer responses:
- "जी हाँ, मैं राहुल शर्मा बोल रहा हूँ।"
- "जी हाँ, आप बात कर सकते हैं।"
- "यह मेरी अपनी रिहायशी संपत्ति है।"
- "मेरे पास संपत्ति के मूल दस्तावेज़ हैं।"
- "मुझे लगभग चालीस लाख रुपये का लोन चाहिए।"
- "मैं नौकरी करता हूँ।"
- "मेरी आय मेरे बैंक अकाउंट में आती है।"
- "मेरी संपत्ति की कीमत लगभग अस्सी लाख रुपये है।"
- "मुझे दस साल की अवधि चाहिए।"
- "मेरे ऊपर इस प्रॉपर्टी पर कोई मौजूदा लोन नहीं है।"

Expected result: The agent communicates naturally in Hindi and follows the same eligibility rules.

## General Testing Checklist

- One question at a time.
- Previously provided information is not requested again.
- Answers given out of order are recognized.
- Customer corrections are handled correctly.
- Disqualifying conditions are detected immediately.
- Existing-loan situations trigger the correct transfer flow.
- Callback requests are converted into clear dates and times.
- Interest rates are not quoted.
- Loan approval is never guaranteed.
- Sensitive information is not requested.
- The agent uses the correct language and gender.
- Calls end with a polite closing.
