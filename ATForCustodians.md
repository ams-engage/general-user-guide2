# For Custodians

## How do I Change the Asset Custody?

> Navigate to: **Asset > Asset Transfer**.

1. Select **New**.

![](images/AT.png "AT")

2. Select the **Transfer Type** as “Only Change Custodian”.

![](images/AT2.png "AT2")

3.Select the **New Custodian**.

![](images/AT3.png "AT3")

4. Search for the user using the search box.

5. Go to the right user and select with the button, you may only select one user.

![](images/AT4.png "AT4")

6. Enter the **Description of Transfer**.

7. Select the **List of Assets** with the **Add** button.

![](images/AT5.png "AT5")

8. Search for the asset using the search box.

9. Check the right asset, you may select more than 1 asset.

![](images/AT6.png "AT6")

10. Select **Submit For Approval**.

![](images/AT7.png "AT7")

11. Select **Confirm**.

![](images/AT8.png "AT8")


## How do I Acknowledge the Transfer record?

> Navigate to **Home**. View your inbox, these are all your **pending tasks**.

1. Select the transaction for your acknowledgement by selecting the link in **blue**.

- In this case, it’s #00000002.

![](images/AT9.png "AT9")

2. Select **Acknowledge**.

![](images/AT10.png "AT10")

3. Select **Confirm**.

![](images/AT11.png "AT11")


## How do I Change the Asset Custody Using Excel Upload?

1. Select **Download Upload Template File**. 
An excel workbook will be downloaded.
If the button is unavailable, notify your agency admin.

![](images/AT12.png "AT12")

2. Open the excel workbook. 
On the **"Asset Transfer”** worksheet:

- **Transaction Cost Centre:** This is the transfer’s cost centre. 
Refer to “Master Data” worksheet for available options.

- **Transfer Type:** To transfer the asset’s custody, indicate “Only Change Custodian”.

- **Original Cost Centre:** To be left blank.

- **New Cost Centre:** To be left blank.


- **Original Custodian:** The person A **currently in charge of the asset** in the system. 
Refer to **“Master Data”** worksheet for available options.

- **New Custodian:** The person B **to-be in charge of the asset**. 
Refer to **“Master Data”** worksheet for available options.

- **Description of Transfer:** What is the description of transfer

**Note:** Only one row should be indicated.

![](images/AT13.png "AT13")

3. On the **“Asset”** worksheet:

- **AMS Asset ID:** The ID of the asset concerning the transfer from person A to person B.

![](images/AT14.png "AT14")

4. Browse for the workbook and select the **“Upload**.

![](images/AT15.png "AT15")

Once the upload is confirmed, the system will check the Excel records for errors. 

When this validation is complete, a summary is shown:

5. If **no critical errors/warnings are found**, select **Confirm to Proceed**.

6. Otherwise, select **Download Validated Excel**.

- The first 2 columns on the validated worksheet will describe the critical errors/warnings that is present in the line item such as “[AMS Asset ID] cannot be found.”

![](images/AT16.png "AT16")

7. A transaction will be created in the search page as **DRAFT**.

![](images/AT17.png "AT17")