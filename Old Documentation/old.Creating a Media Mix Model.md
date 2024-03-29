- Go to [Media Mix Models](https://bimodal.io/mmm-options)
- Select **+ New MMM** in the upper right corner
- Enter the name of the MMM, for example, revenue MMM 2023
    ![Enter Name Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F6d7e24f6-3e66-4222-bd4f-46576df34fe0%2FScreen_Shot_2023-10-31_at_1.38.27_pm.png?table=block&id=fcd10350-4d21-45b9-b487-2e2aa7729688&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=380&userId=&cache=v2)
- Select **Edit** to change settings within the MMM
![Edit Settings Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2Fc80491c7-9f3b-4e54-95cf-f847e8eefa24%2FScreen_Shot_2023-10-31_at_1.39.42_pm.png?table=block&id=743084f6-51e7-4e8c-b482-9cb51f4ba29b&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)
- Select the corresponding **Spend Data**, **Exogenous Data**, **Organic Data** and **Conversion Data** to include in the MMM input. Selecting the right data sources will help you create a more effective model.
    - **Spend Data**: the spend data sources you would like to include in the model.
    - **Exogenous Data**: any data to exclude from the model to reduce the noise.
    - **Organic Data**: data from any non-paid channels.
    - **Conversion Data**: the conversion point to optimize towards.
![Configure MMM Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F7d19784d-6d96-405b-a42c-af6873050a57%2FScreen_Shot_2023-10-31_at_1.42.20_pm.png?table=block&id=a5e577dd-be89-4a3a-9657-8ccfd3b7a32f&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)
- Fine-tune the model with **Advanced Options**:
    - **Iterations**: the times the model is iterating itself ( we recommend using the default setting 2000 times)
    - **Trials**: the times the model will run from scratch (we recommend using the default setting 5 times)
    - **Saturation Curve Shape**: our team will help select the best model for your spending. We recommend keeping it to the default setting.
    - **Earliest Date**: The date you would like the model to trace back to. We recommend including **at least 9 months’ worth of data**.
    - **Latest Date**: The latest date you would like the model to include.
![Advanced Options Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2Faf7b90d8-83a9-4784-919a-18ddd423ab61%2FScreen_Shot_2023-10-31_at_1.45.48_pm.png?table=block&id=937ba768-e955-4bac-ab6f-ce8437304cc1&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=580&userId=&cache=v2)
- **Geo-Holdout Test Calibration Settings**
    - You can include or exclude the new strategy under the geoholdout test in the MMM result by ticking/unticking the box.
    - We recommend including the ones that are successful (indicated in green).
    ![Geoholdout Test Calibration Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F983ab70e-2c63-4ba5-a4d3-f21f87bb3a4a%2FScreen_Shot_2023-10-31_at_1.48.52_pm.png?table=block&id=b7426451-b550-48d3-af3f-bc26a4dfe5de&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)
- Setting the model **active** by switching the button on the top to active.
![Set to Active Screenshot](https://childish-evening-2be.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2Fdb2a3bd2-4ab6-4791-9fcb-408445a57de8%2F9b1ac15a-98c4-476c-8243-d34a445e2e75%2FScreen_Shot_2023-10-31_at_2.42.14_pm.png?table=block&id=c7aa5135-2256-4426-b0fe-a1fd0d8a092b&spaceId=db2a3bd2-4ab6-4791-9fcb-408445a57de8&width=1450&userId=&cache=v2)

Congratulations! You have successfully built your MMM. The model usually takes within 24 hours to populate the result.

Read more about [[old.Interpret the Results of a MMM]]