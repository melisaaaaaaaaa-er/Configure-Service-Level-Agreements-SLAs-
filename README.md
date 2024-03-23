# Configure Service Level Agreements (SLAs)

<h3>Purpose</h3>

- Configure Service Level Agreements (SLAs) on osTicket.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/osticket-images/main/62.png"/>

SLAs are essentially a guarantee/contract by the support team to have a ticket resolved within a given time frame.

We will be adding three new SLAs in this portion of the lab:
- SEV-A,
- SEV-B,
- SEV-C

Navigate to the Manage tab in the Admin Panel.

In the SLA section, click “Add New SLA Plan”.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/osticket-images/main/63.png"/>
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/osticket-images/main/64.png"/>

Put “SEV-A” (Severity-A) in the NAME category, 1 for the Grace Period, and select “24/7” for the Schedule. Click “Add Plan”.

Repeat for “SEV-B” and “SEV-C”.

Schedule refers to when the ticket must be addressed; e.g. a 24/7 ticket must be addressed at all times, even outside of business hours, including weekends.

Grace Period refers to how long you have to resolve the ticket. A Grace Period on 1 hour means the ticket must be resolved within an hour.
