(ticket_numbers)=
# Automatic ticket updates

When a new email is received in the Ask-JGI mailbox an automated
response is generated, which looks something like:
```
Thank you for your Ask-JGI enquiry. Your query will be picked up by a member of the Ask-JGI team soon.

In the meantime please reply to this email to provide any
supplementary information to your question. 
Make sure you include this phrase somewhere in the email:
{AskJGI-110}. 
This helps us to track how the AskJGI service is used.

Suggested additional information:
 1. Your research question
 2. Any relevant papers / draft manuscripts etc.
 3. A description of your data (and a sample if you can send it)
 4. Any relevant analysis scripts/code that you have produced so far.

```
Note the {AskJGI-110} in the text above. The number corresponds to
the Ask-JGI ticket number (110 in this example), which increments with each newly received
query. This number acts as a unique identifier for the email thread,
which is then used to open a new ticket in the Ask-JGI tracker. All
subsequent emails that contain this same identifier will be associated
with the newly created ticket (so that the ticket gets updated with
each new email in the thread).  
