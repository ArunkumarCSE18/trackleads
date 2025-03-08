# trackleads

Overview of the UTM Link Generator & Lead Tracking App
This Bubble application is designed to create UTM links using various UTM parameters and track leads that are generated from different marketing campaigns.

Each lead is automatically created via Zapier, which integrates with your app to capture essential tracking data. The lead data includes:
✅ UTM Parameters (e.g., utm_source, utm_medium, utm_campaign, utm_term, utm_content)
✅ Cost Data (which is initially empty or unknown)

To accurately measure marketing spend and ROI, your app includes a Sync Option that retrieves the cost of a lead from Facebook Marketplace using the Facebook API.

How the Sync Feature Works
1️⃣ Lead Creation via Zapier

When a new lead is captured from an ad or marketing campaign, Zapier automatically sends the data to your Bubble app.
The lead record includes UTM parameters, but the cost field remains empty initially.
2️⃣ Syncing Cost from Facebook API

Your app provides a "Sync" button that triggers an API call to Facebook Marketplace.
It fetches the cost associated with the lead by matching the UTM parameters and campaign details.
The retrieved cost is then updated in your Bubble database.
3️⃣ Updated Lead Data

Once the cost is fetched, the lead record now contains both UTM tracking details and cost data.
This allows for accurate ROI calculation and performance analysis of marketing campaigns.
Key Features of Your Bubble App
🔹 UTM Link Generator: Generates trackable UTM links for marketing campaigns.
🔹 Automated Lead Creation via Zapier: Ensures all leads are captured with proper tracking data.
🔹 Facebook API Integration: Fetches cost data from Facebook Marketplace.
🔹 Sync Button: Allows real-time cost updates for accurate campaign tracking.
🔹 Lead Management Dashboard: Displays all leads with UTM parameters and costs.

Use Case Example
📌 Scenario:

A marketer runs a Facebook Ad campaign with a UTM-tracked link.
A user clicks the ad and fills out a form, creating a lead in Zapier.
Zapier sends the lead details (including UTM parameters) to Bubble.
The marketer clicks Sync in the app, and the cost of that lead is retrieved from Facebook Marketplace.
The lead data is updated with the cost, helping the marketer analyze campaign performance.
