# When a test is complete

The Bimodal platform will indicate when the test is **complete**.

![Test Complete Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F8043db1b-7f2e-42ce-b155-5a1d227bfc34%2FScreen_Shot_2023-10-31_at_11.08.49_am.png?table=block&id=2ef25804-f892-4914-acd2-760c5ca85055&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)

- If the color is <span style="color:red"><b>red</b></span>, then we are not confident that there is enough evidence to show that the new strategy has a significant impact on the region.
- If the color is <span style="color:green"><b>green</b></span>, then we are confident that the new strategy has a significant impact (increase or decrease conversions) on the region.

# Understand the results

By clicking on the name of the test, you will enter the view of the test results.

There are three sections of the results:

- **Summary**: where you can find a summary of the test and results.
- **Graph View**: a graph visualising the results over the test period.
- **Details**: detailed data on the results.

There are three outcomes:

- **We detect an effect and are confident that it is real.**
- **We did not detect the effect or are not confident that the effect is real.**
- **We see an issue with the test that renders it invalid.**

# Summary

Summary

![Geoholdout Summary Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F08b63cf6-1d8a-49fd-8afd-5d471f6f5394%2FScreen_Shot_2023-10-31_at_11.18.20_am.png?table=block&id=01c708a8-975a-45fe-bfe3-3a851935b5ce&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)

This summary shows that the test was ran in Victoria and the measurement conversion is revenue. We predicted that this new strategy should drive an increased revenue during the period from 2022-08-01 to 2022-10-02.

The test results has shown an uplift in revenue of $983,214.

## Graph View

![Geoholdout Graph Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F9ffdebbd-1f4b-4955-b547-089a56618b79%2FScreen_Shot_2023-10-31_at_11.13.33_am.png?table=block&id=74945c5e-394e-4625-98a8-eb2a1c59f528&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=770&userId=&cache=v2)

- The **pink line** displays the outcome of the treatment (a new strategy or campaign) in that particular region.
- <span style="color:orange"><i>The blue line shows the comparable results from other comparable regions in the country. </i></span>
- A **shaded blue area** surrounding the blue line predicts the revenue range that might have been generated in the region without the experiment.
- Hovering the mouse over a specific day on the graph provides an exact conversion prediction.
- In this case, on the date of 2022-09-25, the region has generated $478,273.75 of revenue with the new strategy. We would have expected on average $405,006.13 revenue, with a lower range of $354,380.71 and a higher range of $445,753.41.

# Details

![Geoholdout Details Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F3fc41438-1b3a-47a4-aea3-2ffeaf50251c%2FScreen_Shot_2023-10-31_at_11.18.53_am.png?table=block&id=61318c83-94df-4d56-b4ef-052a4ab4721d&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)

- Click on the **Details** to expand the view.
- The **baseline daily average spend** is the average amount of money spent in the region before any changes.
- The **campaign daily average spend** is the average amount of money spent in the region after the launch of new strategy.
- **CPIC** stands for **Cost Per Incremental Uplift**. Since this test is using revenue as a conversion, it means that we spent $0.26 to drive $1 in additional revenue.
- A **P valu**e, short for “probablity value” indicates the significance of the result. If the p-value is below 0.1 it suggests that our campaign did in fact cause the uplift that we have seen. Alternatively, a high p-value suggests that there is a high probably that we saw this result purely by chance.
- In this case a P value is 0.374, which is much higher than 0.1. It indicates **insufficient evidence** to support the idea that the new campaign or strategy resulted in a significant increased improvement in the outcome.