# leadautomation

This is for teaching people leads automation



1. It starts by pulling company names and websites from your Google Sheet. This is your target list for prospecting.

2. The workflow splits into three parallel processes that run at the same time:

a. The Company Profile AI Agent visits each website and reads through all the content. It figures out what the company does, their products, services, and creates a short summary. This helps you understand if they're a good fit.

b. The Social Media AI Agent scans the website and finds all the social media links. It organizes them by platform (LinkedIn, Twitter, etc.) so you can connect with prospects on multiple channels.

c. The Email Finder scans the HTML of each page and extracts email addresses using smart pattern matching. It pulls out anything that looks like an email.

3. All these emails then go through an automatic verification process using the Reoon API. This checks if the emails are actually valid and deliverable. No more bounced emails!

4. The workflow then combines all this data: company profile, social links, and verified emails into a single dataset.

5. Finally, it writes everything back to your Google Sheet with all the enriched data, ready for your outreach campaigns.

The cool thing is once you set it up, you just add new companies to your sheet and the AI agent handles everything else automatically!

If you want to customize it further, you can add more AI tools like persona identification, or connect it to your CRM or outreach tools.

