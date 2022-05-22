# Chapter 7

## Data Envelopment Analysis

### Non-parametric efficiency measurement with Data Envelopment Analysis
The DEA method is a non-parametric optimisation method of mathematical programming for measuring the relative efficiency of decision-making units (DMUs) that have multiple inputs and outputs. A basic model was introduced by Charnes, Cooper, and Rhodes (1978) and is based on Koopmans activity analysis concept (Koopmans 1951) together with the publications of Debreu and Farrell dealing with radial efficiency measurement (Debreu 1951; Farrell 1957). 

Further advantages beyond multiple inputs and outputs included are the facts that DEA is solely based on empirical data without the need for a priori existing production function and the fact that there is no need to weight factors, as this is done endogenously in the form of virtual inputs and outputs by the mathematics optimisation model. The production process or throughput is seen as a black box. 

The basic idea is to calculate an efficiency frontier that is used as a best practice input-output-combination for the underlying production scenario. DMUs that are on the efficiency frontier are considered as 100% efficient, whereas the relative inefficiency of a DMU can be determined by measuring the distance between individual DMU performance and the efficiency frontier. As the equation above requires n calculations for all n DMUs, the optimisation problem is solved by a linear programming formulation (Charnes, Cooper, and Rhodes 1978, 435–437). The basic mathematical notation is as follows (Wilken 2007, 35):

![image](https://user-images.githubusercontent.com/102478331/169691871-737cda97-8617-4ec9-84b7-0d902828a330.png)

eff is the Abbreviation for efficiency; DMU0 is the DMU with index 0 as exemplary decision unit; s is the Number of outputs to each DMU; m is the Number of inputs to each DMU; u0.j is the Model endogenously weight assigned to the output; v0.i is the Model endogenously weight assigned to the input; y0.j is the Amount of the j output produced by DMU 0; x0.i is the Amount of the i input consumed by DMU 0.

The optimisation method can furthermore be based on constant returns on scale (CRS) in the CCR-model (Charnes, Cooper, and Rhodes 1978) or variable returns on scale (VRS) in the BCC-model (Banker, Charnes, and Cooper 1984) and each case with an input or output orientation. 

![image](https://user-images.githubusercontent.com/102478331/169691971-1c758205-5c1e-44ec-80f1-5f90ba6e66e8.png)

### Hands-on application of Data Envelopment Analysis
The graphic representation of an axis diagram (x,y) (where x the variable of unit entries and y the variable of unit exits) creates the boundaries or the frontiers of efficiency (based on [8] and [26]. We consider 8 units (A,…..,K), one of which has different rates of entry and exit and we put them into a Cartesian diagram of location (figure 2). The inclination of the straight line which passes through the starting point of axes as well as the point of every unit represents the efficiency of the unit. The units with the maximum efficiency are in this case B and I. The remaining units are characterized as non-efficient. The line that passes through the particular units is called efficient frontier which refers to the steady return to scale (SRC) and to CCR Model. The area which is enveloped by this line is called Production Possibility Set. On the contrary, the broken line ΑΒΙK sets the Efficient Frontier which is referred to the variable return to scale (VRC) as well as Banker, Charnes and Cooper Model.

![image](https://user-images.githubusercontent.com/102478331/169692047-6d3f7998-382e-46ce-96eb-8e557431c4db.png)

As far the variable return to scale is concerned, for example unit K will have a greater entry as well as a greater exit than I, but it’s obvious that the absolute efficiency of K is smaller than I. BCC model concerns unit K as sufficient and in this way achieves the increase in the number of units that lay on the efficient frontiers as well as the realistic record of a large number of units which are characterized as efficient in relation to non-efficient (the simplicity and weakness of CCR model is obvious since it considers only two or some units as efficient and the remaining (C, D, Ε, Η, Ζ) as non-efficient. The AB part is defined as Increasing Return to Scale (IRS) whereas ΙK part is considered as Decreasing Return to Scale (DRS). Figure 7 also shows the difference between the efficient frontier line and the regression line. As for the efficiency of units, C unit, which is considered as non-efficient in any care, might improve its efficiency and be included in the efficient frontier of steady return to scale, if it reduces its input (input orientation) preserving the same input taking C2 position. If C unit reduces its input less than before, by preserving the same output it can hold position C3 and can also be included in the efficient frontier of variable return to scale. If Ε unit increases its output by preserving steady its input and hold Ε1 position, then it belongs in the efficient frontier of variable return to scale. E1 unit doesn’t exist in fact, but it’s defined as the virtual DMU whereas, the concept of linearity and of linear combination might consider E1 as a linear combination of I and K. In any case, DEA method is able to define the type of improvement of every unit so as to be found in the efficient frontier.

### MaxDEA - A software for Data Envelopment Analysis
You can download a free version of MaxDEA Basics 8 here: http://maxdea.com/Download.htm. But why MaxDEA?

- Easy to use. It does not require installation and has user-friendly interface. It is very easy to prepare the dataset. You needn’t indicate what are the inputs and outputs by field (variable) names or special arrangement of your data. 
- Easy to backup your DEA models and dataset. Everything is saved in a single file. The software, your dataset and the settings for your DEA model are all integrated into the single program file, and it is the only file needed for MaxDEA Ultra, so it is very convenient to backup. After closing and reopening MaxDEA Ultra, your database and model settings are still there unchanged.
- Most important of all, MaxDEA Ultra provides nearly all the possible combinations of up-to-date DEA models. To use a combination of multiple DEA models, just choose all the relevant options. For example, Network-Malmquist model with weakly disposable bad outputs can be achieved by choosing the settings for Network, Undesirable outputs, Weak disposability and Malmquist, at the same time.

#### Step 1: Open the software

#### Step 2: Import the dataset



## Sources:
Charnes, A., William Wagner Cooper, and E. Rhodes. 1978. “Measuring the Efficiency of Decision Making Units.” European Journal of Operational Research 2 (6): 429–444. doi:10.1016/0377-2217(78)90138-8.
Cooper, William Wager, L. M. Seiford, and K. Tone. 2007. Data Envelopment Analysis: A Comprehensive Text with Models, Applications, References and DEA-Solver Software. Boston: Springer US.
Cooper, William Wagner, L. M. Seiford, and J. Zhu. 2011. “Data Envelopment Analysis: History, Models, and Interpretations.” In Handbook on Data Envelopment Analysis, edited by W. W. Cooper, L. M. Seiford, and J. Zhu, 1–39. Boston: Springer US.
Debreu, G. 1951. “The Coefficient of Resource Utilization.” Econometrica 19 (3): 273–292. doi:10.2307/1906814.
Farrell, M. J. 1957. “The Measurement of Productive Efficiency.” Journal of Royal Statistical Society 120 (3): 253–290.


Hands-on application: https://www.researchgate.net/publication/308349794_The_Data_Envelopment_Analysis_Method_and_the_influence_of_a_phenomenon_in_organizational_Efficiency_A_literature_review_and_the_Data_Envelopment_Contrast_Analysis_new_application
