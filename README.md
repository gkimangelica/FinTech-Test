# FinTech

Source Data:
Largets US Retailers
https://data.world/garyhoov/largest-us-retailers-2015

Save data in your local file system.

**Option 1: MANUAL RUN**

1. Edit below files to replace "LOCAL_PATH_AVALOQTEST" to local path where the source excel file will be read and target files to be written/saved.

---Extract_Load.java
---Transform_Clean.java
---Transform_DataMart.java
---Workflow_TEST.java  (Data Pipeline)

2. The code should be run accroding to the same order stated above.
_NOTE: Codes are auto-generated from Talend Open Stidio which was used for development of the pipeline_

**Option 2: RUN USING TALEND OPEN STUDIO**

1. Download Talend Open Studio for Big Data here: https://www.talend.com/products/big-data/big-data-open-studio/
2. For the purposes of the excercise, only local file system was used as source and target.
3. Run TOS_BD-win-x86_64 from the TOS_BD-20200219_1130-V7.3.1 after downloading the software.
4. Import the talend.project from Talend jobs folder.
5. Run the job on the same orders stated below OR run the Workflow 0.1.
---Extract 0.1
---Transform 0.1
---DataMart 0.1
