Overview

In a typical data flow life cycle, data flows from relational / non-relational source systems to OLAP systems passing through layers of data warehouses and data marts. Business Intelligence systems employ analytical data processing systems for analyzing vast volumes of data which is generally pre-aggregated for extremely fast data analytics. This brings a perception of saturation in terms of data analytics requirements to many professionals. The key point that is missing in the big picture is that the data analytics depends upon the capabilities of the end user to analyze the data and determine analytics.

Generally the methods employed by business users are to slice and dice different measurable facts / KPIs by different dimensions, using different visualizations for problem decomposition and problem space identification, time-based trend-analysis, etc. All these methods employ simple statistical computations and analysis. There is a branch of statistical science which can use complex specialized algorithms that are designed for focused categories of problems to discover patterns in large volumes of data, which is also known as predictive analysis. Based on the identified patterns, the data is extrapolated for forecasting and prediction purposes. This branch of data science is generally known as Data Mining.

The purpose of data mining is to identify the patterns and dataset for a particular domain of problems by programming the data mining model using a data mining algorithm for a given problem. Once the problem space is identified, even machine learning can be employed to design a system that can extract patterns in the given dataset with a lot more automation and without the need for specialized programming for each given problem.

SQL Server Analysis Services contains a variety of data mining capabilities which can be used for data mining purposes like prediction and forecasting. This tutorial aims to explain the process of using these capabilities to design a data mining model that can be used for prediction.

In SSAS, the data mining implementation process starts with the development of a data mining structure, followed by selection of an appropriate data mining model. Once the model is built, it needs to be trained with a dataset which would be used as the source of prediction. Once the model has been trained, it is used for prediction on the actual data and the results are validated to determine the accuracy with which the model predicted the data correctly. Finally the business users are provided access to the deployed model using the Data Mining Add-In for Excel. This tutorial will explain of all these aspects. To comfortably follow this tutorial, it is recommended to have a reasonable understanding of data warehouse as well as SSAS dimensional modeling.

The course is structured as follows:

    Data Mining Basics
        Data Mining Process
        Data Mining Algorithms
    Data Mining Model Development
        Developing Data Mining Structure
        Developing Data Mining Model
    Validation and Prediction
        Testing Data Mining Model
        Prediction Analysis
    Data Mining from OLAP Sources
        Developing OLAP Structure
        Data Mining Relationships
    Querying and Reporting
        Querying Data Mining Model
        Data Mining Office Add-In
