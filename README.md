# Meeting-Scheduling
An automation project that automates the process of updating CRM and email automation.

Objective:
This project is made to demonstrate the power of autoamtion in a normal businesss workflow.

Working:
The working of this project starts from the home page of the website, when a potential client visits the website of the company and goes to the contact section and fills in the details like his name, contact details, and the problem he is facing, the data will be stored in the database the company explicitly uses. 

This is the usual workflow any company's website follows. But this project gets implemented after this.

We make use of webhooks and AI APIs to do the following.

We take the data that is entered in the database and update the CRM; in this case, we have taken a normal Excel Sheet.
Then immediately we send the details about their pain points, business industry, and stuff to our LLM model for better analysis and email writing. This email is then automatically sent to the client who just filled out the form, asking for approval for a quick meeting to discuss further. The email prompt is designed to have a hook, engaging body, and a call to action part. 

When we get the approval, we will send another mail thanking them for their time and we will also be sending the meeting link.
On the other hand, the calendar of the company will also get updated with the time the client chooses and create an event with the meeting link.
