>((E.WhatGeoholdoutsAre))

Before you can run a Geoholdout test, you must decide what market to run the test in. To determine the best market for running a Geoholdout test, refer to the [Test Market Report](https://bimodal.io/geoholdout/marketReport).

# Selecting a Test Market

In the sidebar under 'Geoholdout' select 'Test Market Report'. 

The Test Market Report presents your possible test markets in order based on their suitability for a Geoholdout test. You will be able to see three key indicators of suitability:

**Duration** indicates the minimum length of time you would need to be able to run a test in order to detect the Smallest Detectable Uplift.

**Smallest Detectable Uplift** describes the smallest change in the market that the test will be able to detect. You should have some idea of the size of change you expect to see in the market; do **not** select a test market whose Smallest Detectable Uplift is larger than your expected change, as it will not be able to detect the change.

**Quality** provides an indication of the reliability of the market's results:
- High (Green) indicates a market with highly reliable outputs. Select a High quality market for best results. 
- Medium (Yellow) indicates a market that is broadly good, with some (volatility?). It is recommended that Medium quality markets are only selected if there are no High quality markets that meet your needs; or by experienced users with a clear rationale for their use.
- Low (Red) indicates a market likely to produce *un*reliable outcomes. Low quality markets are **not** recommended for use.

The first column (Region) will indicate the market in question, these can be singular (eg. 'victoria'), or separated by commas (eg. 'south_australia, victoria') indicating a market of both those regions together.

If you have specific types of market you wish to analyse, you can narrow the report using the drop-down menus at the top:
- **Region** will allow you to filter the test markets to only those including a particular region.
- **Conversion** will allow you to filter the test markets to only those using a particular outcome metric (Eg., Revenue, Add-to-carts, etc.)

>((Advanced Menu))

# Running a Geoholdout

Once you have selected the test market, you are ready to run your Geoholdout test.

## Communicate with your Team

It is crucial you communicate the test you are going to run to your team. As you are testing a specific region against the performance of the rest of the market, ensure that:
- The intended changes are made in that region.
- The intended changes are **not** being made in the rest of the market.
- No *other* changes are being made in that region.
- No *other* changes are being made in the rest of the market.

If any of the above requirements are violated, the results from your test may not be valid, which would be a waste of time and resources.

## The Geoholdout Menu

In the sidebar under 'Geoholdout' select 'Tests'

This page will list any Geoholdout tests you have previously ran including:
- The date range they covered.
- Their location.
- Their conversion metric.
- What channels they used.
- Their status (Pending, In Progress, Complete?)

## Creating a Geoholdout

>((Explain E.channels/how to select them for testing?))

To create a new test select '+ Add Test' in the top-left of the screen
- Give your new test a name that you will be able to recognise.
- Select your conversion metric to base the test on.
- Select the direction of the expected change (Increase or Decrease)
- Select the test region you decided on based on the [[T.TestMarketReport|Test Market Report]]
- Select the channels you wish to perform the test on.
- Select any Exogenous Data you may wish to include ((What does this actually look like?))
	- Exogenous Data is any data not part of the test that you may expect to impact your results, such as a sale period.
	  > (What does this look like for selecting though?)
- Add a brief description to help interpret the test at a later date. This should contain any details you deem important, but suggested details include:
	- A brief description of what was being tested.
	- The period it was being tested across.
	- What you expect to find.

# Interpreting a Geoholdout

When your test is finished, the status will update to 'Complete'. The colour of the 'Complete' indicator provides a brief overview of the result of your test:
- Green indicates confidence that the test resulted in a meaningful change in the region.
- Red indicates the absence of evidence that the test resulted in any meaningful change in the region.

For more details, click the name of the test, which will provide you with the Test Summary.

## Test Summary

The table on the right will provide a brief summary of the test, including the Total Uplift, which represents the total amount the test market differed over the period from what we would have expected otherwise.
### Interpreting the Geoholdout Graph

On the left, you will see a graph of the test market (labelled 'treatment') compared to what we would expect to see in the market if we had not made any changes (labelled 'control').
You will also see a shaded blue area indicating the upper and lower bounds for the 'control'.
>Because the test is *predicting* what the market would look like if you had not made any changes, it cannot provide the exact values. As such, this grey band represents the upper and lower bounds of the range that we are confident the 'true' value is in.

The dotted line indicates the point at which the start date of the test.
>((Example Graph))

Hovering your mouse over any day will show the recorded and estimated values for that day.
>((Example mouse-over))

### Interpreting the Details Menu

Below the Summary on the right is an expandable 'Detail' pane. Expanding this menu will reveal:
- Baseline Daily Average Spend - The average money spent in the region per day before any changes were made.
- Campaign Daily Average Spend - The average money spent in the region per day during the campaign period.
- CPIC (Cost Per Incremental Change) - How much you spent on the campaign for each unit of outcome.
	- Eg., if your outcome was revenue, this would be cost per dollar of revenue; if your outcome was subscriptions, this would be cost per subscription.
- P Value - This represents how confident the test is that a meaningful change has occurred, ranging from 0 to 1.
	- A P value below 0.1 indicates confidence that any observed change is meaningfully different from the control.
	- A P value above 0.1 indicates that we cannot be confident the test produced any meaningful difference. Any changes observed are insufficiently distinguishable from what could have been obtained by luck.
>((E.Pvalues))




