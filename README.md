# ERD Diagram for Understanding the Relationships
![ERD](https://user-images.githubusercontent.com/77080621/130872571-8a237397-dbcf-452f-9369-94d19510ff32.PNG)

# Snapshot of Tables with all fields
![tablesUsed](https://user-images.githubusercontent.com/77080621/130873931-e514f64d-478d-41d8-8a63-40f2faf0385c.PNG)

# Goal Of the Project:

In this project we will create Matrix report in SSRS (SQL Server Reporting Services) with a practical example. The below screen shot will show you the dataset, datasource and SQL used to create matrix report.

![1](https://user-images.githubusercontent.com/77080621/130875089-d27f227a-70e8-4df4-ad1b-51726173ad1b.PNG)

parameter @discription is used to be used for Drop down option created to choose the Items (Please refer to SQL file to check the SQL used for configuration).
Here is the screen shot of Report Data in Visual Studio after defining the two datasets.

![2](https://user-images.githubusercontent.com/77080621/130875581-d5405590-63a9-4a79-aaf0-42e730408e8a.PNG)

Here is the screen shots which explain the process of configuring the parameter in Report Data bar in visual Studio.

![3](https://user-images.githubusercontent.com/77080621/130875752-b488a05b-ce57-4ee5-b66a-2ae8ea647a6d.PNG)
![4](https://user-images.githubusercontent.com/77080621/130875758-c4dad686-b37e-47d4-a502-ca1d715dbce3.PNG)

Drag and drop Matrix from SSRS toolbox to data region.

![5](https://user-images.githubusercontent.com/77080621/130876052-b9d2ce88-a3f8-4676-882b-274599b1199e.PNG)

You will right click into Data box shown in above image, hover over on Insert Column >> then click on Inside Group -Right option. Again you will click into Data box shown in above image, hover over on Insert Column >> then click on Outside Group -Left option. Then fill in the values by clicking on the small table button on very right of each box and final results will look like the below image. Right click on CustomerCategoryBox and pick the Text Box Properties. Then pick the khaki color on the fill in color option. You can also adjust font of different boxes according to your choice.

![6](https://user-images.githubusercontent.com/77080621/130877088-1fed9c8f-09bd-4919-9aa3-894224368887.PNG)

When you click on Preview tab on top, you will have to choose an option from Items? category, multiple options could also be chosed for accessing different reports. I have chosen option 'USB Rocket Launcher (Gray) item and then click on view button on right. Here is how the report will look like.

![1](https://user-images.githubusercontent.com/77080621/130877573-370d17cd-bf9e-422a-958c-a3873f74ae68.PNG)

You can change the coloring and font as you like for this report.
