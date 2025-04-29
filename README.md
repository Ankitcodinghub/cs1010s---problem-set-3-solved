# cs1010s---problem-set-3-solved
**TO GET THIS SOLUTION VISIT:** [CS1010S – Problem Set 3 Solved](https://www.ankitcodinghub.com/product/cs1010s-problem-set-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115085&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1010S - Problem Set 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Functional Abstraction

There are several sub-questions in each task. Make sure you answer every one of them in the template file provided before finalizing your submission on Coursemology.

In mathematics, Pascal’s triangle is a triangular array of the binomial coefficients. In much of the Western world, it is named after French mathematician Blaise Pascal, although other mathematicians studied it centuries before him in India, Persia (Iran), China, Germany, and

Italy.

To construct a Pascal’s triangle, we begin by numbering the first row as n = 0. The second row would be n = 1, the third row would be n = 2, etc. Each row contains n + 1 elements with the first element numbered as k = 0. the second element k = 1, and so on until the last element, which is k = n.

On row 0, we simply write the number one. To derive the elements for the subsequent rows, we use this algorithm—add the number directly above and to the left with the number directly above and to the right of a specific element to find the new number for that element. If either the number to the left or right is not present, we will substitute a zero in its place.

1

1 1

1 2 1

1 3 3 1

1 4 6 4 1

1 5 10 10 5 1

Mathematically, the number of each element is calculated with the same formula for calculating combinations:

For example, 5 choose 3. i.e., the sixth row (n = 5) fourth element (k = 3) in the figure would be:

Note that you can simplify the computation by cancelling out (3 × 2 × 1) in the computation above.

1

Questions

1. Implement the function int factorial(int n) that takes in a positive integer n and returns n factorial.

2. What happens to your function when n≥ 13? Explain why.

3. Implement the function int choose(int n, int k) that takes as inputs two integers, where 0 ≤n&lt; 30 and 0 ≤k≤n, and returns the value of . For example, choose(13, 2) returns 78.

4. Are you able to make use of the factorial function in choose ? Explain why.

void pascal_triangle(int row)

printf or cout )

5. Finally, implement the functionthat takes one integer as input and prints (i.e., using the requested row of the Pascal’s Triangle with one space between the numbers . For example, pascal_triangle(15) prints:

1 15 105 455 1365 3003 5005 6435 6435 5005 3003 1365 455 105 15 1 Assumption: Your functions are only required to work for 0 ≤n&lt; 30 and 0 ≤row&lt; 30.

Hint: Take note of the size limits of the types.

Hint 2: Because pascal_triangle is required to print the output instead of returning as a value, do remove all debugging printf before submitting on Coursemology, lest they interfere with the output.

S M T W T F S

1 2

3 4 5 6 7 8 9

10 11 12 13 14 15 16

17 18 19 20 21 22 23

24 25 26 27 28 29 30

The solution to this problem can be rather complex, so we will use functional abstraction to break it down into smaller parts. You are advised to implement and test each part (by defining a suitable main function) before moving on the the next part.

You are to implement the following functions:

1. bool is_leap_year(int year) to determine if a given year is leap.

Note that not all years which are multiples of 4 are leap. Centuries are not leap unless they are multiples of 400.

2. int days_in_month(int month, int year) that takes the month (an integer from 1 to 12) and year, and returns number of days in the given month (an integer from 1 to 31).

For example. days_from_epoch(10, 1, 1970) returns 9 because it is nine days away from the epoch.

5. Finally, void display_month(int month, int year) to print the specific month of the given year. The output should contain a header for the day of week ” S M T W T F S” and the numbers should be right aligned under their respective day of the week.

S M T W T F S

1 2

3 4 5 6 7 8 9

10 11 12 13 14 15 16

17 18 19 20 21 22 23

24 25 26 27 28 29 30

S M T W T F S

1 2 3 4 5 6 7

8 9 10 11 12 13 14

15 16 17 18 19 20 21

22 23 24 25 26 27 28

29 30 31

As this problem set is on functional abstraction, you should reuse these functions whenever possible.
