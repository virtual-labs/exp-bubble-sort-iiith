#### Please use the [reference](https://github.com/virtual-labs/ph3-exp-dev-process/blob/main/pedagogy/README.org) document to fill this template.  Follow the [link](https://github.com/virtual-labs/ph3-exp-dev-process/tree/main/sample/pedagogy) to view a sample pedagogy document.

## Pedagogy
<p align="center">


<br>
<b> Experiment : 	To Study & Verify Bubble Sort Algorithm. <a name="top"></a> <br>
</p>

<b>Discipline | <b> Computer Science and Engineering
:--|:--|
<b> Lab | <b> Data Structures 1
<b> Experiment|     <b> Bubble Sort: algorithm and complexity


<h4> [1. Focus Area](#LO)
<h4> [2. Learning Objectives and Cognitive Level ](#LO)
<h4> [3. Instructional Strategy](#IS)
<h4> [4. Task & Assessment Questions](#AQ)
<h4> [5. Simulator Interactions](#SI)
<hr>

<a name="LO"></a>
#### 1. Focus Area :
|Sr. No |	Focus Area	|
|:--    |:--| 
|1.| Experimentation| 


#### 2. Learning Objectives and Cognitive Level


|Sr. No |LO ID	|Learning Objective	| Cognitive Level | Action Verb|
|:------|:-----|:------------------|:----------------|:-----------|
|1.     | 145  | Students will be able to demonstrate the distinction between Bubble Sort and the other sorting algorithms by listing out the differences| Recall | List|
|2.| 146 | Students will be able to sort an unsorted array of numbers by applying the algorithm | Apply | Apply|
|3.| 147 |Students will be able to demonstrate knowledge of time complexity and hence prove that the time complexity for the given algorithm is O(n*n) | Understand | Explain |

<br/>
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="IS"></a>
#### 3. Instructional Strategy
|Method |	Assessment	| Instruction Strategy
|:--|:--|:--| 
A list of numbers to be sorted is given. Students use primitive actions (compare and swap on adjacent elements) to sort the array. <br>Through this, they gain hands-on experience and knowledge on how bubble sort works. | Ask them questions like the following to test their comprehension <br>True or False: Bubble sort will take N operations to find the position of 1 element in the list of N elements. |Expository |


<a name="AQ"></a>
#### 4. Task & Assessment Questions:

Read the theory and comprehend the concepts related to the experiment. [LO1, LO2, LO3]
<br>

|LO ID |	Learning Objective	| Task  | Assessment Question|
|:--|:--|:--|:-:|
|145| Students will be able to demonstrate the distinction between Bubble Sort and the other sorting algorithms by listing out the differences |Understand the difference between the algorithms. Observe how each of them performs on small and large lists. | Q1. Which algorithm given below is the most efficient for sorting large lists? <br>1. Quicksort <br>2. Bubble Sort <br>3. Insertion Sort <br> Q2. What advantage does Bubble Sort possess over other sorting techniques? <br>1. It is the simplest technique. <br>2. It is the most efficient algorithm in terms of its time complexity. <br>3. It can detect whether the input is already sorted. <br>4. Options 1 and 2|
|146| Students will be able to sort an unsorted array of numbers by applying the algorithm |System gives a list of numbers to be sorted. Student applies compare or swap, as appropriate for the situation, according to the algorithm. Student detects after a few applications of operations that the list is sorted. | Q1. How many operations will it take on an average to find the largest number out of 10 numbers? <br>1.    100 operations. <br>2.    10 operations. <br>3.    25 operations. <br>4.    None of these <br>Q2.  How many iterations will it take to sort the array A={1,2,4,3} ? <br>1. 3 <br>2. 1 <br>3. 4 <br>4. 2|
|147| Students will be able to demonstrate knowledge of time complexity and hence prove that the time complexity for the given algorithm is O(n*n) | Derive the best case and worst case time complexities for a given algorithm and compare them. Observe the difference between a regular Bubble Sort and an optimized Bubble Sort algorithm.  | <br>Q1. What is the best case and worst case time complexity of an Optimized Bubble Sort algorithm? <br>1. O(n) and O(n^2) <br>2. O(n^2) and O(n^2) <br>3. O(n) and O(n^3) <br>4. O(n^2) and O(n^3) <br>Q2. Which of the following is not true. <br>1. Time complexities of best case and worst case of Bubble Sort are the same. <br>2. Bubble Sort has a more desirable time complexity than that of Merge Sort. <br>3. Only the best case time complexity varies from normal Bubble Sort to Optimized Bubble Sort. |
<div align="right">
    <b><a href="#top">↥ back to top</a></b>
</div>
<br/>
<hr>

<a name="SI"></a>

#### 5. Simulator Interactions

 
|SNo.| What student will do | What simulator will do  | Purpose|
|:---|:---------------------|:------------------------|:-------|
|LU1 - D (Learning Unit 1 - Demo)|                             |
|1. | Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the functions including a movable bar which is labelled as “Min.Speed” and “Max.Speed” on both ends and a “Comments” box below. |To see the buttons and understand their purpose from their labels.|
|2. | Move the speed bar according to convenience. | Set the speed of the execution of the demo model according to the speed bar. | To adjust the speed of the execution of the demo unit.|
|3. | Click the “Start” button. | Start executing the demo model. | To begin the execution of the demo model.|
|4. | Click the “Pause” button. | Pause the execution at that very instant. | To pause the execution of the demo model.|
|5. | Click the “Next” button. | Move forward with the execution. | To resume the execution after paused, or to quickly go through all the steps of the execution.|
|6. | Click on the “Reset” button. | Reset the execution and display a new array. | To stop the execution of the demo model and to observe the execution on a new array set.|
|7. | Observe the “Comments” box | Display the total number of comparisons and swaps performed and display “The sort is Complete” once the array is sorted. | To be aware of the total number of comparisons and swaps that have taken place till that point in the execution.|
LU1 - P (Learning Unit 1 - Practice)
|1. |Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the  functions including a “Comments” box below. | To see the buttons and understand their purpose from their labels.|
|2. | Compare the first two adjacent elements. If the value on the right side is smaller than the value on the left side, click on the “Next” button. | Move marker to the next two adjacent elements. | To move on with the iteration of the array.|
|3. | Compare two adjacent elements. If the value on the right side is smaller than the value on the left side, click on the “Swap” button. | Swap the positions of the elements in question. | To sort the elements in those two positions.|
|4. | Click on the “Reset” button. | Reset the execution and display a new array. | To stop the practice with the current array and move on for practice with a new array. |
|5. | Observe the “Comments” box. | Display the corresponding comments for each move performed by the user. | To check if the the move performed was correct or not.|
|LU1 - E (Learning Unit 1 - Exercise)|
|1. | Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the functions including a “Comments” box below. | To see the buttons and understand their purpose from their labels.|
|2. | Click the “Start” button. | Start executing the demo model. | To begin the execution of the demo model.|
|3. | Click the “Next” button. | Move marker to the next two adjacent elements. | To move on with the iteration of the array.|
|4. | Click the “Swap” button. | Swap the positions of the elements in question. | To sort the elements in those two positions.|
|5. | Click the “Undo” button. | Revert back to the position that was present before the latest move. | To provide ability to go back on already performed moves. 
|6. | Click the “Submit” button. | Evaluate the array and display in the comments box if it is sorted or not. | To check if the user has understood the concept clearly and has got the right solution in the exercise problem. |
|7. |Click the “Reset” button. | Reset the progress and display a new array. | To stop the practice with the current array and move on for practice with a new array.|
|8. | Observe the “Comments” box. | For each move, display the total number of iterations of the array that have taken place. | To know when to stop iterating and if the result submitted is a sorted array or not.|
|LU2 - D (Learning Unit 2 - Demo)|
|1. | Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the functions including a movable bar which is labelled as “Min.Speed” and “Max.Speed” on both ends and a “Comments” box below. | To see the buttons and understand their purpose from their labels to help perform Optimized Bubble Sort.|
|2. | Move the speed bar according to convenience. | Set the speed of the execution of the demo model according to the speed bar. | To adjust the speed of the execution of the demo unit. |
|3. | Click the “Start” button. | Start executing the demo model. | To begin the execution of the demo model.||
|4. | Click the “Pause” button. | Pause the execution at that very instant. | To pause the execution of the demo model.|
|5. | Click the “Next” button. | Move forward with the execution. | To resume the execution after paused, or to quickly go through all the steps of the execution. |
|6. | Click on the “Reset” button. | Reset the execution and display a new array. | To stop the execution of the demo model and to observe the execution on a new array set.|
|7. | Observe the “Comments” box | Display the total number of comparisons and swaps performed and display “The sort is Complete” once the array is sorted. | To be aware of the total number of comparisons and swaps that have taken place till that point in the execution.|
|LU2 - P (Learning Unit 2 - Practice)|
|1. | Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the functions including a “Comments” box below. | To see the buttons and understand their purpose from their labels.|
|2. | Compare the first two adjacent elements. If the value on the right side is smaller than the value on the left side, click on the “Next” button. | Move marker to the next two adjacent elements. | To move on with the iteration of the array.|
|3. | Compare two adjacent elements. If the value on the right side is smaller than the value on the left side, click on the “Swap” button. | Swap the positions of the elements in question. | To sort the elements in those two positions.|
|4. | Click on the “Reset” button. | Reset the execution and display a new array. | To stop the practice with the current array and move on for practice with a new array.|
|5. | Observe the “Comments” box. | Display the corresponding comments for each move performed by the user. | To check if the the move performed was correct or not according to Optimized Bubble Sort algorithm.|
|LU2- E (Learning Unit 2 - Exercise)|
|1. | Look at the array to be sorted and observe the buttons displayed. | Display a list of numbers (an array) and buttons to perform the functions including a “Comments” box below. | To see the buttons and understand their purpose from their labels.|
|2. | Click the “Start” button. | Start executing the demo model. | To begin the execution of the demo model.|
|3. | Click the “Next” button. | Move marker to the next two adjacent elements. | To move on with the iteration of the array.|
|4. | Click the “Swap” button. | Swap the positions of the elements in question. | To sort the elements in those two positions 
|5. | Click the “Undo” button. | Revert back to the position that was present before the latest move. | To provide ability to go back on already performed moves.
|6. | Click the “Submit” button | Evaluate the array and display in the comments box if it is sorted or not.|To check if the user has understood the concept clearly and has got the right solution in the exercise problem.|
|7. | Click the “Reset” button. | Reset the progress and display a new array. | To stop the practice with the current array and move on for practice with a new array.|
|8. | Observe the “Comments” box. | For each move, display the total number of iterations of the array that have taken place. | To know when to stop iterating and if the result submitted is a sorted array  or not, with respect to the Optimized Bubble Sort algorithm.|







