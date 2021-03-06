## **Decreasing Traffic Fatality in the U.S**

The United States is one of the busiest countries in terms of road traffic with nearly 280 million vehicles in operation. In 2018, there were some 12 million vehicles involved in crashes in the United States. Road collisions incur huge economic costs at a national level, which includes a burden on the health, insurance and legal systems. Moreover, they can have negative social implications for the families of those involved as well as on local communities.

**Data**
---
The data set below shows the distribution of fatal car accidents throughout the U.S. This is a sample from 2012 of reported fatal collisions per billion miles including possible causes such as speeding, alcohol impairment, distraction, prior accidents, as well as car insurance premiums and losses incurred by insurance companies. There are 51 rows indicating states and 6 columns indicating the causes.

I use the a dataset created by five-thirty-eight, available [here](https://datahub.io/five-thirty-eight/bad-drivers)

| Field Name      | Type                                                    | 
| :---         | :---              | 
| **state**   | *string (default)*        | 
| **number of drivers involved in fatal collisions per billion miles**     | *number (default)*          |
| **percentage of drivers involved in fatal collisions who were speeding**     | *integer (default)*          | 
| **percentage of drivers involved in fatal collisions who were alcohol-impaired**     | *integer (default)*          | 
| **percentage of drivers involved in fatal collisions who were not distracted**     | *integer (default)*          | 
| **percentage of drivers involved in fatal collisions who had not been involved in any previous accidents**    | *integer (default)*          | 
| **car insurance premiums ($)**     | *number (default)*          | 
| **losses incurred by insurance companies for collisions per insured driver ($)**     | *number (default)          | 

###### *Original Source: National Highway Traffic Safety Administration, 2012*

**Goals**
---
The goal of this project is to categorize States that have similar profiles in terms of causes of fatal car collisions into clusters using Principal Components Analysis(PCA) and K-means Clustering. Rather, than coming up with a costly, one-size-fits-all policy nation-wide strategy or action plan to reduce the number of road accidents, it would be valuable to develop a State-oriented plan. The second goal is to show the total number of drivers involved in an fatal accident by cluster-group, thereby reflecting where a greater number of accidents occur. The findings can be insightful for the government and policy-makers on where to focus efforts in reducing traffic fatalities.

**Table and Contents**
---
* [Datasets](https://github.com/mishaisran/Projects/tree/master/Decreasing%20Traffic%20Fatality%20in%20the%20U.S/Datasets) - Datasets using in the analysis.
* [Notebook](https://github.com/mishaisran/Projects/blob/master/Decreasing%20Traffic%20Fatality%20in%20the%20U.S/Notebook/traffic_fatality.ipynb) - Jupyter notebook used to clean, organize and analyze data.
* [Readme](https://github.com/mishaisran/Projects/blob/master/Decreasing%20Traffic%20Fatality%20in%20the%20U.S/Readme.MD) - An overview of the dataset, method and summary of analysis.
* [License](https://github.com/mishaisran/Projects/blob/master/LICENSE) - MIT License


**Packages and Softwares**
---
---
<pre>
Contributor  : <a href=https://github.com/Al-Cap>Misha Isran</a>
</pre>

<pre>
Languages    : Python 3.8.3
Tools/IDE    : Jupyter Notebook
Libraries    : pandas 1.0.5, sklearn, matplotlib, seaborn
Methods      : Data wrangling, plotting, dimensionality reduction, and K-means clustering.
</pre>
  </tbody>
</table>
