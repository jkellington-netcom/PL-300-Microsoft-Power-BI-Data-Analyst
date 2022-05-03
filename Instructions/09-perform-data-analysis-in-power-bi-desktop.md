---
lab:
    title: 'Perform Data Analysis in Power BI Desktop'
    module: 'Module 9 - Identify Patterns and Trends'
---


# **Perform Data Analysis in Power BI Desktop**

**The estimated time to complete the lab is 45 minutes**

In this lab you will create the **Sales Exploration** report.

In this lab you learn how to:

- Create animated scatter charts

- Use a visual to forecast values


### **Task 1: Get started – Sign in**

In this task you will setup the environment for the lab by signing in to Power BI.

*Important: If you have already signed in to Power BI in a previous lab, continue from the next task.*

1. To open Microsoft Edge, on the taskbar, click the Microsoft Edge program shortcut.

 	![Picture 7](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image1.png)

1. In the Microsoft Edge browser window, navigate to **https://powerbi.com**.

 	*Tip: You can also use the Power BI Service favorite on the Microsoft Edge favorites bar.*

1. Click **Sign In** (located at the top-right corner).

 	![Picture 5](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image2.png)

1. Enter the account details provided to you.

1. If prompted to update the password, reenter the provided password, and then enter and confirm a new password.

 	*Important: Be sure to record your new password.*

1. Complete the sign in process.

1. If prompted by Microsoft Edge to stay signed in, click **Yes**.

1. In the Microsoft Edge browser window, in the Power BI service, in the **Navigation** pane, expand **My Workspace**.

 	![Picture 4](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image3.png)

1. Leave the Microsoft Edge browser window open.

## **Exercise 1: Create a Scatter Chart**

In this exercise you will create a scatter chart that can be animated.

### **Task 1: Create an animated scatter chart**

In this task you will create a scatter chart that can be animated.

1. Rename **Page 1** as **Scatter Chart**.

	![Picture 67](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image14.png)

2. Add a **Scatter Chart** visual to the report page, and then position and resize it so it fills the entire page.

	![Picture 18](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image15.png)

	![Picture 75](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image16.png)

3. Add the following fields to the visual wells/areas:

	The labs use a shorthand notation to reference a field. It will look like this: **Reseller** **\|** **Business Type**. In this example, **Reseller** is the table name and **Business Type** is the field name.

	- Legend: **Reseller \| Business Type**

	- X Axis: **Sales \| Sales** 

	- Y Axis: **Sales \| Profit Margin**

	- Size: **Sales \| Quantity**

	- Play Axis: **Date \| Quarter**

	![Picture 39](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image17.png)

	*The chart can be animated when a field is added to the **Play Axis** well/area.*

4. In the **Filters** pane, add the **Product \| Category** field to the **Filters On This Page** well/area.

5. In the filter card, filter by **Bikes**.

	![Picture 40](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image18.png)

6. To animate the chart, at the bottom left corner, click **Play**.

	![Picture 41](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image19.png)

7. Watch the entire animation cycle from **FY2018 Q1** to **FY2020 Q4**.

	*The scatter chart allows understanding the measure values simultaneously: in this case, order quantity, sales revenue, and profit margin.*

	*Each bubble represents a reseller business type. Changes in the bubble size reflect increased or decreased order quantities. While horizontal movements represent increases/decreases in sales revenue, and vertical movements represent increases/decreases in profitability.*

8. When the animation stops, click one of the bubbles to reveal its tracking over time.

9. Hover the cursor over any bubble to reveal a tooltip describing the measure values for the reseller type at that point in time.

10. In the **Filters** pane, filter by **Clothing** only, and notice that it produces a very different result.

11. Save the Power BI Desktop file.

## **Exercise 2: Create a Forecast**

In this exercise you will create a forecast to determine possible future sales revenue.

### **Task 1: Create a forecast**

In this task you will create a forecast to determine possible future sales revenue.

1. Add a new page, and then rename the page to **Forecast**.

	![Picture 66](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image20.png)

2. Add a **Line Chart** visual to the report page, and then position and resize it so it fills the entire page.

	![Picture 19](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image21.png)

	![Picture 74](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image22.png)

  

3. Add the following fields to the visual wells/areas:

	- Axis: **Date \| Date**

	- Values: **Sales \| Sales** 

	![Picture 46](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image23.png)

4. In the **Filters** pane, add the **Date \| Year** field to the **Filters On This Page** well/area.

5. In the filter card, filter by two years: **FY2019** and **FY2020**.

	![Picture 47](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image24.png)

	*When forecasting over a time line, you will need at least two cycles (years) of data to produce an accurate and stable forecast.*

  

6. Add also the **Product \| Category** field to the **Filters On This Page** well/area, and filter by **Bikes**.

	![Picture 48](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image25.png)

7. To add a forecast, beneath the **Visualizations** pane, select the **Analytics** pane.

	![Picture 20](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image26.png)

8. Expand the **Forecast** section.

	![Picture 50](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image27.png)

	*If the **Forecast** section is not available, it’s probably because the visual hasn’t been correctly configured. Forecasting is only available when two conditions are met: the axis has a single field of type date, and there’s only one value field.*

9. Click **Add**.

	![Picture 51](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image28.png)

10. Configure the following forecast properties:

	- Forecast length: 1 month

	- Confidence interval: 80%

	- Seasonality: 365

11. Click **Apply**.

	![Picture 52](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image29.png)

12. In the line visual, notice that the forecast has extended one month beyond the history data.

	*The gray area represents the confidence. The wider the confidence, the less stable—and therefore the less accurate—the forecast is likely to be.*

	*When you know the length of the cycle, in this case annual, you should enter the seasonality points. Sometimes it could be weekly (7), or monthly (30).*

13. In the **Filters** pane, filter by **Clothing** only, and notice that it produces a different result.

14. Save the Power BI Desktop file.


### **Task 2: Finish up**

In this task you will complete the lab.

1. Select the **Scatter Chart** page.

2. Save the Power BI Desktop file.

3. To publish the file to your **My workspace**, on the **Home** ribbon tab, from inside the **Share** group, click **Publish**.

	![Picture 23](Linked_image_Files/10-perform-data-analysis-in-power-bi-desktop_image46.png)

4.  Close Power BI Desktop.
