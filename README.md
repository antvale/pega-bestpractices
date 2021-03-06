# Pega Best Practices
Contains some of the most important Pega best practices

## 1. Data Modeling
1.1 A developer **should** verify the data model with a Lead System Architect before creating data objects or properties. 

1.2 Establishing the data model before creating and working with data saves future development time and minimizes the volume of errors that might impact application performance.

1.3 Put supplemental case processing data often exists outside of data objects, such as user preferences entered during case processing that influence the case lifecycle, in a separate data object class named with the same name of the case type

1.4 Create the data model by using the Data Explorer first, keeping reuse and inheritance in mind

1.5 Using the Configure a view screen is a best practice when only a small number of fields are needed (for example, as part of patch updates)

1.6 
