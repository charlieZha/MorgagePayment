---
title       : Morgage Payment
subtitle    : 
author      : Yizhou Zha
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Brief Description
This App could be use to caculate the morgage payment by entering the morgage payment rate, total loan amount, loan term.
As a common choice, it caculate the Principal & Interest loan annually, monthly and weekly payment.

---

## How to use
<!--html_preserve--><div class="container-fluid">
<div class="row-fluid">
<div class="span12" style="padding: 10px 0px;">
<h1>Morgage Payment</h1>
</div>
</div>
<div class="row-fluid">
<div class="span4">
<form class="well">
<label for="Rate">Rate:</label>
<input id="Rate" type="text" value="null"/>
<label for="LA">Total Loan Amount</label>
<input id="LA" type="number" value="null"/>
<label for="Time">Loan Term (Yearly)</label>
<input id="Time" type="number" value="null"/>
<div>
<button type="submit" class="btn btn-primary">Submit</button>
</div>
</form>
</div>
<div class="span8"></div>
</div>
</div><!--/html_preserve-->
<ol>
<li>Enter the loan interest rate into the Rate box as 0.0xx
<li>Enter the total loan amount into the Total Loan Amount box
<li>Enter the loan term as how many years you are going to pay the loan
<li>After All info been entered, press the Submit button, the result will be displayed at the right side of the window.
<ol>

---

## The Result
### The result deatil will be displayed as:
1. At the top of the list, it will display user entered loan detail 
2. followed by the annually loan payment
3. monthly loan payment  
4. weekly loan payment.

---

## Future Development

1. More type loan payment
Beside the Principal & Interest loan payment, we also should develop the interest only payment which is aim to the investment users

2. More Prediction
It also should develop more prediction sessions as loan rate prediction, real estate market brief trend prediction

3. Charts
It also very necessary to introduce charts into the App, especially for these prediction session which is easier for user to make right decision



