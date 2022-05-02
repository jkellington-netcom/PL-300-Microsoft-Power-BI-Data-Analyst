---
lab:
    title: 'Create a Power BI Dashboard'
    module: 'Module 8 - Create Dashboards'
---


# **Create a Power BI Dashboard**

**The estimated time to complete the lab is 15 minutes**

In this lab you will create the **Sales Monitoring** dashboard.

In this lab you learn how to:

- Pin visuals to a dashboard

- Use Q&A to create dashboard tiles

## **Exercise 1: Create a Dashboard**

In this exercise you will create the **Sales Monitoring** dashboard. The completed dashboard will look like the following:

![Image of the completed dashboard, comprising three tiles.](Linked_image_Files/09-create-power-bi-dashboard_image1.png)

### **Task 1: Get started – Sign in**

In this task you will setup the environment for the lab by signing in to Power BI.

*Important: If you have already signed in to Power BI in a previous lab, continue from the next task.*

1. To open Microsoft Edge, on the taskbar, click the Microsoft Edge program shortcut.

    ![Picture 42](Linked_image_Files/09-create-power-bi-dashboard_image2.png)

2. In the Microsoft Edge browser window, navigate to **https://powerbi.com**.

    *Tip: You can also use the Power BI Service favorite on the Microsoft Edge favorites bar.*

3. Click **Sign In** (located at the top-right corner).

    ![Picture 41](Linked_image_Files/09-create-power-bi-dashboard_image3.png)

4. Enter the account details provided to you.

5. If prompted to update the password, reenter the provided password, and then enter and confirm a new password.

    *Important: Be sure to record your new password.*

6. Complete the sign in process.

7. If prompted by Microsoft Edge to stay signed in, click **Yes**.

8. In the Microsoft Edge browser window, in the Power BI service, in the **Navigation** pane, expand **My Workspace**.

    ![Picture 40](Linked_image_Files/09-create-power-bi-dashboard_image4.png)

9. Leave the Microsoft Edge browser window open.

### **Task 2: Create a dashboard**

In this task you will create the **Sales Monitoring** dashboard. You will pin a visual from the report, and add a tile based on an image data URI, and use Q&A to create a tile.

1. In the Microsoft Edge browser window, in the Power BI service, open the **Sales Analysis** report.

2. In the **Overview** page, set the **Year** slicer to **FY2020**.

    ![Picture 4](Linked_image_Files/09-create-power-bi-dashboard_image17.png)

3. Set the **Region** slicer to **Select All**.

    *When pinning visuals to a dashboard, they will use the current filter context. Once pinned, the filter context cannot be changed. For time-based filters, it’s a better idea to use a relative date slicer (or, Q&A using a relative time-based question).*

4. To create a dashboard and pin a visual, hover the cursor over the **Sales and Profit Margin by Month** (column/line) visual.

5. At the top-right corner, click the pushpin.

    ![Picture 43](Linked_image_Files/09-create-power-bi-dashboard_image18.png)

6. In the **Pin to Dashboard** window, in the **Dashboard Name** box, enter **Sales Monitoring**.

    ![Picture 3](Linked_image_Files/09-create-power-bi-dashboard_image19.png)

7. Click **Pin**.

    ![Picture 1](Linked_image_Files/09-create-power-bi-dashboard_image20.png)

8. Open the **Navigation** pane, and then open the **Sales Monitoring** dashboard.

    ![Picture 44](Linked_image_Files/09-create-power-bi-dashboard_image21.png)

9. Notice that the dashboard has a single tile.

    ![Picture 45](Linked_image_Files/09-create-power-bi-dashboard_image22.png)

10. To add a tile based on a question, at the top-left of the dashboard, click **Ask a Question About Your Data**.

    ![Picture 7](Linked_image_Files/09-create-power-bi-dashboard_image23.png)

    *You can use the Q&A feature to ask a question, and Power BI will respond will a visual.*

11. Click any one of the suggested questions beneath the Q&A box, in blue boxes.

12. Review the response.

13. Remove all text from the Q&A box.

14. In the Q&A box, enter the following: **Sales YTD**

    ![Picture 11](Linked_image_Files/09-create-power-bi-dashboard_image24.png)

15. Notice the response of **(Blank)**.

    ![Picture 14](Linked_image_Files/09-create-power-bi-dashboard_image25.png)

16. Extend the question with: **in year FY2020**.

    ![Picture 12](Linked_image_Files/09-create-power-bi-dashboard_image26.png)

17. Notice the response is now **$33M**.

    ![Picture 13](Linked_image_Files/09-create-power-bi-dashboard_image27.png)

18. To pin the response to the dashboard, at the top-right corner, click **Pin Visual**.

    ![Picture 15](Linked_image_Files/09-create-power-bi-dashboard_image28.png)

19. When prompted to pin the tile to the dashboard, click **Pin**.

    ![Picture 17](Linked_image_Files/09-create-power-bi-dashboard_image29.png)

20. To return to the dashboard, at the top-left corner, click **Exit Q&amp;A**.

    ![Picture 16](Linked_image_Files/09-create-power-bi-dashboard_image30.png)

### **Task 5: Edit tile details**

In this task you will edit the details of two tiles.

1. Hover the cursor over the **Sales YTD** tile, and then at the top-right of the tile, click the ellipsis, and then select **Edit Details**.

    ![Picture 50](Linked_image_Files/09-create-power-bi-dashboard_image36.png)

2. In the **Tile Details** pane (located at the right), in the **Subtitle** box, enter **FY2020**.

    ![Picture 19](Linked_image_Files/09-create-power-bi-dashboard_image37.png)

3. Click **Apply**.

    ![Picture 20](Linked_image_Files/09-create-power-bi-dashboard_image38.png)

4. Notice that the **Sales YTD** tile displays a subtitle.

    ![Picture 21](Linked_image_Files/09-create-power-bi-dashboard_image39.png)

5. Edit the tile details for the **Sales, Profit Margin** tile.

6. In the **Tile Details** pane, in the **Functionality** section, check **Display Last Refresh Time**.

    ![Picture 22](Linked_image_Files/09-create-power-bi-dashboard_image40.png)

7. Click **Apply**.

    ![Picture 23](Linked_image_Files/09-create-power-bi-dashboard_image41.png)

8. Notice that the tile describes the last refresh time (which done when loading the data model in Power BI Desktop).
