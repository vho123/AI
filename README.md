#0 Preparation

Open this URL in new browser tab, https://github.com/vho123/AI

CLick on below files,

![image](https://user-images.githubusercontent.com/50817966/228743354-1fb49876-0689-4415-a707-02e27411c03d.png)

Click "Raw"

![image](https://user-images.githubusercontent.com/50817966/228743460-5c21e2f6-ebe3-4d43-bdc1-86aa7e6abe55.png)

Right click and "Save as..."

![image](https://user-images.githubusercontent.com/50817966/228743661-a23bf7c3-1054-4b59-87cc-677158a646d6.png)

Store at a location like C:\ or desktop (Remember this path!!)

Repeat on other CSV file.

For the ZIP file, simply click download.

![image](https://user-images.githubusercontent.com/50817966/228744158-2d8447e2-0069-4531-8d70-5c2110e1e2bf.png)


#1 Power Automate RPA
![image](https://user-images.githubusercontent.com/50817966/227774884-39157ec0-c625-4214-af33-ce8c0bcb699a.png)

Download URL (weather): https://data.weather.gov.hk/weatherAPI/opendata/opendata.php?dataType=CLMMAXT&year=%LoopIndex%&rformat=csv&station=%Station%
![image](https://user-images.githubusercontent.com/50817966/227776113-5388a11c-ba28-41a1-ab58-d015ef91d0bc.png)

Download URL (holiday): https://www.1823.gov.hk/common/ical/en.json
![image](https://user-images.githubusercontent.com/50817966/227775014-ea2d69f7-330c-4bc3-bb6b-c171d8dcfec4.png)

#2 Training AI builder

Login to Power Platform Admin Center
https://admin.powerplatform.microsoft.com/home

Click New

![image](https://user-images.githubusercontent.com/50817966/227869168-a85f65e6-d0e8-4dc5-8328-6cf950f0c847.png)

Enter name and type

![image](https://user-images.githubusercontent.com/50817966/227869456-1213cbf4-67ee-4971-a4f9-e4788c4a6252.png)

Enable Create database; 

Next

![image](https://user-images.githubusercontent.com/50817966/227869722-59f3ef2b-1e2f-4928-8441-3ccd025623fc.png)

Save and done!

Wait when it is deploying. 

Go to Power Apps. 

make.powerapps.com

Swicth environment.

![image](https://user-images.githubusercontent.com/50817966/227870037-6af2e852-247c-4c14-81b1-64cac516dfca.png)




Import data from CSV
![Step 1](https://user-images.githubusercontent.com/50817966/227844722-ad9e5ac6-579c-44a5-8552-b8c028c0d865.png)

![Step 1 1](https://user-images.githubusercontent.com/50817966/227844793-15a3bbd1-75ff-47f3-8b9e-c6dab20e3baf.png)

![Step 1 2](https://user-images.githubusercontent.com/50817966/227909959-c4e1d835-6ae6-4c3f-b462-51bffb9f392b.png)

![Step 1 2 1](https://user-images.githubusercontent.com/50817966/227909845-1583d533-5865-472a-96ce-7fe8d5e701b0.png)

![Step 1 4](https://user-images.githubusercontent.com/50817966/227844841-74d4f952-9c5c-46cf-98bd-1a70118636b0.png)

![Step 1 5](https://user-images.githubusercontent.com/50817966/227844856-bed2cc13-da56-4034-bac4-c2703a7f356b.png)

![Step 1 6](https://user-images.githubusercontent.com/50817966/227844865-6c2b718c-df1b-492d-9bac-eaf5d4a42192.png)

![Step 1 7](https://user-images.githubusercontent.com/50817966/227844883-4d354015-2927-41bc-830a-948359bdc44d.png)

![Step 1 8](https://user-images.githubusercontent.com/50817966/227844899-6908c8ef-6376-4788-ac9e-aae0a47bb5a5.png)

![Step 1 9](https://user-images.githubusercontent.com/50817966/227844904-a9ed9154-5277-4d07-b111-d523383c337b.png)

Repeat the above steps on another file.

Make sure the data type is detected correctly.

![image](https://user-images.githubusercontent.com/50817966/228717241-f6ec412a-ac32-4435-bb70-50bccef7622b.png)

![image](https://user-images.githubusercontent.com/50817966/228717412-1f2518b7-ad68-4a81-81a9-7c4a40d82ed1.png)

![Step 1 10](https://user-images.githubusercontent.com/50817966/227844916-fcb18cc5-f764-4738-9448-1692814f91f2.png)

After creating tables for training data and prediction data, let's go to create prediction model.

Start Trial if you have not enabled that before.

![image](https://user-images.githubusercontent.com/50817966/228712376-75ff807d-e11e-44be-a0ec-bbd3c5720f73.png)

![Step 2](https://user-images.githubusercontent.com/50817966/227847437-06bc948e-da11-4ee1-99a7-4cbaa94cc323.png)

![Step 2 1](https://user-images.githubusercontent.com/50817966/227847465-9eeadbee-2120-4236-83fb-c54a74587fba.png)

![Step 2 2](https://user-images.githubusercontent.com/50817966/227847482-3d2e7d9e-8bef-4d5a-ac96-5bc93c891838.png)

![Step 2 3](https://user-images.githubusercontent.com/50817966/227847497-f12128ff-16b1-4993-868b-b16c5b868590.png)

![Step 2 4](https://user-images.githubusercontent.com/50817966/227847506-634b7bcb-cc74-4679-a73a-055d14921dc1.png)

![Step 2 5](https://user-images.githubusercontent.com/50817966/227847515-f95ac697-4dad-497b-b588-ed6b78bc955e.png)

![Step 2 6](https://user-images.githubusercontent.com/50817966/227847529-55db4cbf-ade9-4682-a684-21f95e2d97cc.png)

![Step 2 7](https://user-images.githubusercontent.com/50817966/227847542-0db289f9-84a4-425b-a8d4-55d04b72554e.png)

![image](https://user-images.githubusercontent.com/50817966/227853581-2c306d73-7957-46b8-8ba9-41030dbfd1ca.png)


#3 Power Automate Cloud Flow

Login Power Automate 

make.powerautomate.com

Import package
![image](https://user-images.githubusercontent.com/50817966/227775312-860d89b0-2c66-4334-b0b5-51cb2939297f.png)

![image](https://user-images.githubusercontent.com/50817966/227853900-81592d8b-1e99-4454-b0a0-2777445c5be8.png)

![image](https://user-images.githubusercontent.com/50817966/227911203-cfe4a7f3-3a61-433e-97cb-1d174cf1da8d.png)

![image](https://user-images.githubusercontent.com/50817966/227911929-c403c402-6ba5-4c04-80b1-1f453e09e235.png)

Add the connections needed.
![image](https://user-images.githubusercontent.com/50817966/227848960-931d19ae-9c16-4f84-afa0-f3d59c274fc7.png)

Azure blob storage
![image](https://user-images.githubusercontent.com/50817966/227849065-a486f147-70ea-493e-a1ad-c5876ebbbd1d.png)

![image](https://user-images.githubusercontent.com/50817966/227775398-dfd0383e-3deb-4c60-9299-ebbfb43efc08.png)

Storage account name: hhoadls2

Access key: CULu9gpUO7InX2aQFjVGGrDtr/4E9FahfuK9jrHGSHySlosOihAeyGXlXBQU/WdZrJ90y2V1wacBcxYlZS6FRQ==

Dataverse

![image](https://user-images.githubusercontent.com/50817966/227849239-77933f5c-6b12-4aeb-9961-3c0a639eb6d8.png)

![image](https://user-images.githubusercontent.com/50817966/227849382-f29ce751-a811-4447-85fa-3bd676946a3a.png)

![image](https://user-images.githubusercontent.com/50817966/227849471-c305dba5-e9ee-46aa-baa6-1645a9bfe652.png)

![image](https://user-images.githubusercontent.com/50817966/227849572-f099f68b-7daf-4224-a066-0da413027f52.png)

![image](https://user-images.githubusercontent.com/50817966/227849773-a481c5ea-f57c-416a-841e-85f058312a0c.png)

![image](https://user-images.githubusercontent.com/50817966/228719200-b9c94523-e224-4247-bd52-80ec31c5faeb.png)

Click edit to open the flow content

![image](https://user-images.githubusercontent.com/50817966/228719413-6520c300-5fd1-4dda-9fad-91af8538fbbb.png)

![image](https://user-images.githubusercontent.com/50817966/228719528-22619e2a-430b-4c71-a901-f8bc3b4b15c9.png)


Add an action after "get Traffic last week"

![image](https://user-images.githubusercontent.com/50817966/228719690-2b091268-c043-4d2c-b9a6-eb9716610cf3.png)


Choose an operation - AI Builder - Predict

![image](https://user-images.githubusercontent.com/50817966/227861206-bdd42a39-753b-4988-a036-818330102f55.png)

Choose a new model you published.

![image](https://user-images.githubusercontent.com/50817966/227862093-2375a244-156d-40e7-8269-e855b0c8f1bf.png)

Do the field mapping: Temperature,Humidity,Is_Holiday,Holiday_soon_2days_before,Holiday_ending_soon,Weekday,Traffic_last_week

![image](https://user-images.githubusercontent.com/50817966/227862318-70248d11-f38f-4d05-b682-41a5833e8194.png)

Add a new step

Choose operation - Dataverse - Add a new row

![image](https://user-images.githubusercontent.com/50817966/227863248-c46520e8-7471-4c48-b5a9-30ae204affaf.png)

Select the table we created at the beginning (prediction result table).

![image](https://user-images.githubusercontent.com/50817966/227863451-b1034d94-aea8-487a-9711-1c3405514182.png)

Do the field mapping: date,Temperature,Humidity,Is_Holiday,Holiday_soon_2days_before,Holiday_ending_soon,Weekday,Traffic_last_week,Prediction(from AI builder output)

Save the flow, turn on the flow

![image](https://user-images.githubusercontent.com/50817966/227912870-f426da43-5f1b-437b-b803-2d7da8f050f3.png)

Run the flow and view the flow detail by clicking on the temp-stamp

![image](https://user-images.githubusercontent.com/50817966/227913600-033978cd-58eb-4b80-b209-5f0c9faaef58.png)

Once completed, check if a new row added to table "Sales Model Prediction"

![image](https://user-images.githubusercontent.com/50817966/228720644-8dbddc2e-c5f0-40a4-9b0a-bd5a482a8fa1.png)

Congratulation! You have completed the lab exercise.



