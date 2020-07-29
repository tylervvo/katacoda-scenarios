Suppose you have an executive who is interested in getting regular updates about the health of your services. Rather than sending a manual update every month, you instead create a self service executive dashboard.

### Step 1 - top level metrics

This could be anything, but for the sake of argument, let’s say it’s 
1. Revenue 
2. Checkout uptime

To create a revenue metric we will first need to find that data. 

#### Create your revenue metric 
Start by navigating to `https://app.datadoghq.com/logs`{{copy}} and searching for `add search term here`{{copy}}

Once you’re confident this is the data that will allow you to track revenue, you’re going to want to store that metric over time. 

- Start by copying your query
- Navigate to **Generate Metrics** under the Logs navigation item
- Select **New Metric** 
- Paste your query
- Choose your measure
- Finish by choosing **Create Metric**

Up next...Create your checkout uptime metrics
