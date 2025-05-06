# ie507-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [IE507 Lab 5 Solved](https://www.ankitcodinghub.com/product/ie507-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97670&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE507 Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Instructions:

We will practice modeling a transportation problem and a facility assignment problem in this lab. These problems can be formulated as appropriate optimization problems with an associated objective function and constraints. Two-dimensional decision variables are useful in these problems, and we will focus on using such two-dimensional variables in model building using pyomo.

We will continue to model problems by loading information from files in this lab. We will also continue modeling problems with integer variables, wherever required.

Recall, to load directly from a file with comma separated values (.csv file), we used pandas library. The construct pandas.read csv helps to read contents from a .csv file. Please check https: //pandas.pydata.org/pandas-docs/stable/getting_started/index.html to know more about pandas library.

In this lab, accessing the data frame using iloc is discussed in detail. For more details on this iloc function, please see https://pandas.pydata.org/pandas-docs/stable/reference/api/ pandas.DataFrame.iloc.html

Please follow the instructions given below:

• Please use different notebooks for solving different problems.

• The notebook name for Exercise 1 should be YOURROLLNUMBER IE507 Lab5 Ex1.ipynb.

• Similarly, the notebook name for Exercise 2 should be YOURROLLNUMBER IE507 Lab5 Ex2.ipynb. • Please post your doubts in MS Teams or Moodle so that TAs can clarify.

For more details on pyomo, please consult https://pyomo.readthedocs.io/en/stable/index. html.

There are only 2 exercises in this lab. Try to solve all problems on your own. If you have difficulties, ask the Instructors or TAs.

Only the questions marked [R] need to be answered in the notebook. You can either print the answers using print command in your code or you can write the text in a separate text tab. To add text in your notebook, click +Text. Some questions require you to provide proper explanations; for such questions, write proper explanations in a text tab.

After completing this lab’s exercises, click File → Download .ipynb and save your files to your local laptop/desktop. Create a folder with name YOURROLLNUMBER IE507 Lab5 and copy your .ipynb files to the folder. Also copy the .csv files to the folder. Then zip the folder to create YOURROLLNUMBER IE507 Lab5.zip. Then upload only the .zip file to Moodle.

The deadline for today’s lab submission is tomorrow, 17th September 2020, 11 59 PM Indian Standard Time (IST).

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 05 16-September-2020

Exercise 1: Transportation Problem [15 marks]

A customer has contacted Jai Logistics for transporting air-conditioner units (ACUs) from ware- houses to markets. There are eight warehouses, each of which has some truck-loads of ACUs in stock. These ACUs must be transported to eight markets for satisfying the demand. You are intern- ing at Jai Logistics and you are given the task of finding out how many ACUs must be transported from each warehouse to each market.

<ol>
<li>[R] Let C[w,m] be the cost of transporting one truck-load of ACUs from w to m. Write a general optimization problem to minimize the total transportation cost. Use appropriate notations and define appropriate sets to be used in the optimization problem.</li>
<li>Use the costs, demands and available stocks from Table 1 to create a .csv file, similar to that used in the practice exercise. You can use the transport.txt file uploaded in Moodle to create the .csv file. Name the file as lab5 ex1.csv. Use simple and appropriate names for the headers.</li>
<li>Copy the file to colab environment.</li>
<li>Use pandas to load the .csv file contents.</li>
<li>Create a model using pyomo to solve your optimization problem. Use the loaded contents of .csv file to create your model. Use iloc function of pandas library to access the data frame contents obtained from the .csv file.</li>
<li>Use cbc solver to solve your optimization problem. In your code, remember to specify which variables are integers.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Table 1: Cost of Transporting a Truck-load of AC Units

</div>
</div>
<div class="layoutArea">
<div class="column">
Warehouses Indore Ahmedabad 427 Bengaluru 1179 Chennai 1409 Delhi 1123 Kolkata 1712 Lucknow 886 Mumbai 546 Nagpur 495 Demand 75

</div>
<div class="column">
Jodhpur Vellore 617 1270 1623 372 1823 59 533 2265 2079 1830 760 1965 817 1045 1062 1113 300 250

</div>
<div class="column">
Markets

Kanpur Hyderabad Patna Raipur Cuttack

982 915 943 974 1265 2072 257 1373 1052 959 2127 358 1422 1304 811

467 1896 941 1232 1348 1499 1929 439 691 128 83 1759 395 795 1332 1232 905 1211 1187 1487 1121 802 1125 474 801 200 400 100 50 70

</div>
<div class="column">
Avail.Stock

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>100
250
200
200
150
</pre>
90 290 200

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="7">
<li>[R] Report the number of truck-loads of ACUs that are transported (report only those values that are nonzero) from warehouses to markets. Report the total cost also.</li>
<li>[R] Suppose the Bengaluru-Patna link is disrupted and no transportation is possible on the link. Without changing the pyomo model, how will you solve this problem? You are only allowed to change the .csv file.</li>
<li>[R] Report the new solution value and the nonzero flows in the network.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 05 16-September-2020

Exercise 2: Assigning Locations [20 Marks]

Mansarov Constructions Inc. has to build n ∈ N different types of factories, one at each of the n locations. The cost of constructing (setup cost) the ith facility at the jth location provided in the Table 2 below. Mansarov Constructions Inc. wants to minimize the sum of the costs of assigning all the facilities to the locations.

Factory Location

1 2 3 4 5 6 7 8 9 10 11 12

<ol>
<li>1 &nbsp;19 12 18 19 22 21 17 20 16 15 21 24</li>
<li>2 &nbsp;22 22 19 21 22 24 18 17 21 19 22 23</li>
<li>3 &nbsp;18 23 20 20 21 22 19 18 20 23 19 19</li>
<li>4 &nbsp;18 21 20 18 17 19 24 16 18 16 20 24</li>
<li>5 &nbsp;23 17 16 19 24 21 23 21 20 21 22 21</li>
<li>6 &nbsp;23 20 17 16 20 23 22 25 24 19 17 20</li>
<li>7 &nbsp;22 18 17 15 22 24 23 20 22 19 23 20</li>
<li>8 &nbsp;24 22 21 23 18 17 16 19 24 21 20 23</li>
<li>9 &nbsp;21 20 17 18 16 24 19 17 18 20 21 23</li>
<li>10 &nbsp;19 22 21 24 20 23 19 18 23 24 25 20</li>
<li>11 &nbsp;20 24 22 20 23 19 18 16 22 24 21 24</li>
<li>12 &nbsp;22 23 24 20 21 20 20 19 17 19 20 22</li>
</ol>
Table 2: Set up cost of factories at different locations

<ol>
<li>[R] Write a mathematical model to solve the assignment problem explained above. Define all the variables and constraints clearly. Use appropriate notations and define appropriate sets to be used in your optimization problem.</li>
<li>Construct a pyomo model for this problem for a general n. You can assume that the cost matrix is given as data from a txt file and can be loaded as a numpy array.</li>
<li>Use the data in Table 2 to make a .txt file for your model. You can use the setupcosts.txt file uploaded in Moodle to create the .txt file. Name the file as lab5 ex2.txt.</li>
<li>Copy the file to colab environment.</li>
<li>Use numpy.loadtxt to load the data from lab5 ex2.txt file into a numpy array.</li>
<li>Adapt the general pyomo model you created, to use the data loaded from the lab5 ex2.txt file.</li>
<li>Use cbc solver to solve your optimization problem. In your code, remember to specify which variables are integers.</li>
<li>[R] Solve the problem and report which facility must be opened at each location.</li>
<li>[R] Now change the integer variables in your model to continuous variables, and re-solve the
problem. Report the solution (only the non-zero values of the solution).
</li>
<li>[R] Are the optimal costs for both problems same? Are the values of the variables still integer-valued? If yes, explain why.</li>
<li>Will the solution to the continuous problem become fractional (non-integer) if the costs are changed to non-integer values? Try changing the costs to different values and test whether the solution to the LP becomes fractional for any of them.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 05 16-September-2020

12. [R] Now suppose that, due to some reason, facility 1 cannot be assigned to location 4, facility 11 cannot be assigned to location 3 and facility 5 cannot be assigned to location 9. What changes in your pyomo model or in lab5 ex2.txt file will you make? Make these changes, and solve the integer problem and report the solution.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
