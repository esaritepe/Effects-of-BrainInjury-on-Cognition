# Effects of Traumatic Brain Injury on Cognition 

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Brain_network.png" alt="Brain Network" width="200"/>
</p>

Description
------------
### Background
* There's been some exciting potential for a new neuroimaging analysis technique called structural covariance networks (SCNs), especially for traumatic brain injury (TBI) research. However, the literature on the most reliable brain measurement is not well-established.

### Project Goals
* Using a neuroimaging software called FreeSurfer, three anatomical measurements were collected (cortical thickness, surface area, and volume). These brain measurements were used to create SCNs so that the graph theory properties of the biological neural networks can be studied. 
* Neuropsychological data were also collected from TBI subjects. Tests that determine the cognitive abilities of the subjects were used. 

### Modeling
* Multiple linear regression models were created to determine any correlation between graph theory parameters and neuropsychological test scores. Statistical analyses were also performed to verify the accuracy and precision of the data. 
* One alternate brain measurement, surface area, was found to have 170% more reliable results than the more commonly used cortical thickness. 
* Made suggestions to the scientific field to establish surface area as the standard brain measurement for SCN studies, ensuring more reliable results in the future. 

### Limitations
* Since this project was completed in an academic setting, the data cannot be included in the repository for confidentiality reasons.

File Structure
--------------
In the repository, you will see three notebooks each covering one of the brain measurements used in the project. In each of these notebooks, you will find Python code that performs the following:
  * Importation of brain measurement datasets
  * A correlation matrix comparing similarities between the different brain regions
  * Generation of brain network graphs
  * Merging data with the neuropsychological scores
  * Linear regression models comparing the graph theory parameters of brain networks and neuropsychological test scores
  * Statistical analyses (Standard error of the estimate, Adj, R-squared, etc.) to verify the accuracy and precision of the results 

Results
--------
![Surface Area](https://raw.github.com/esaritepe/Effects-of-BrainInjury-on-Cognition/screenshots/surface_area.png)
