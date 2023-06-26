# Microsoft-fabric
By switching into Data Engineering, will see the following the item such as Lakehouse (Preview) which is used for storing big data for cleansing, querying , reporting and sharing
![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/27c692bb-5886-467b-848a-dcf882caf06f)
## The Lakehouse (Preview) 
![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/7e96a5b7-3473-4533-8647-d497ebbefa5b)

Create a lake house by giving the naming convention to it. 


![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/1187aa0d-53b1-447c-989e-75d35324f7bf)


If you go to my workspace setting you will see the license mode (Trial)

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/f269e8e9-ae70-4654-b64c-b6bfdbc90c23)


# How to get Data into Lakehouse

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/42df0c01-114f-4c25-9776-3242a64dfbf6)


Once you open the New Dataflow Gen2, you will get the following the option such as excel, SQL server, Import CSV.


![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/783d1c20-122e-482d-b423-d7723679b67f)

Then Upload the EXCEL file from the Adventure work

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/54b9c73b-cb66-49b7-8598-9b80057e32da)

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/6fdfe695-0426-4b33-b0cd-53c810d31762)

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/6ede1d4e-f9f9-405a-8dd8-b975b439453c)

### After the create you will get the following in a Power Query:

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/2a1b2338-658e-43b4-9dd1-430823c3114d)

In a Microsoft fabric, the lineage option in a Power Query gives you a powerful option once you extracting data into it; Such as Managed Columns, Reduced Rows, Sort, Combine, Transform and CDM.

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/f9f6f46b-34b8-4e1b-b0a9-265620ab223e)

Then, you can choose different destination such as Azure SQL database, Lakehouse, Azure Data Explorer, and Azure Synapse Analytics (SQL DW) to load into it.

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/e5ac24ac-0cfe-4e3f-9e95-76d71a50294f)

After choosing the Lakehouse as a destination need to Setup a connection for it as below:

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/ae51eebb-3274-4568-a04c-2187025dc41f)

After selecting the next you will get the following destination option, under the My workspace and choose the appropriate workspace that you have created and then NEXT.

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/328a84e3-4f86-4a60-83cc-aeb15aa0bee5)

You will get an option such as append, replace as below and then save the setting as below.

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/28b53c1b-774f-4259-a820-66d1c9a902a8)

Finally, publish it to Lakehouse:

![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/8cc47815-4f1c-454a-825e-0b14068e8c86)

Dataflow 2 is published.


![image](https://github.com/ijaz-lab/Microsoft-fabric/assets/78338522/c8382834-56e5-4e84-bf5f-de8fbb5b9f66)

#### Lakehouse  the ability to explore the data. It give the read only experience NOT insert, update and delete options.




