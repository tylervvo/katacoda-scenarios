Suppose you have an executive who is interested in getting regular updates about the health of your services. Rather than sending a manual update every month, you instead create a self service executive dashboard.

### Step 1 - Top level metrics

This could be anything, but for the sake of argument, let’s say it’s 
1. Revenue 
2. Checkout uptime

To create a revenue metric we will first need to find that data. 

#### Create your Dashboard

We are going to start off with a blank dashboard by 
1. Navigating to the **Dashboards**
2. Choosing **New Dashboard**
3. Adding a dashboard title
4. Selecting **New Screenboard**

*Don't forget to ★ your dashboard to find again*

#### Create your revenue metric 
Start by navigating to `https://app.datadoghq.com/logs`{{copy}} and searching for `service:store-cartlogger`{{copy}}

Once you’re confident this is the data that will allow you to track revenue, you’re going to want to store that metric over time. 

- Create a measure on your **price** and **cost** by clicking on the item and selecting **Create measure for @item.price** and **@item.cost**
- Start by copying your query
- Navigate to **Generate Metrics** under the Logs navigation item
- Select **New Metric** 
- Paste your query
- Choose your measure
- Finish by choosing **Create Metric**

Now that you’ve created your metric, 
- Select **See in Metric Explorer**
- From here you can view your new metric 
- Get started with our Executive Dashboard by choosing **Export to new Dashboard** → *Add Details* → **View Dashboard**

Up next... Create your checkout uptime metrics
