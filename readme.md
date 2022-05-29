# Loan Data from Prosper Exploration
## by David Yacoub


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
with feature documentation available here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&source=editors&ust=1614606248511000&usg=AOvVaw3SHouTo689BwhUMP8PrnHm

and This data dictionary explains the variables in the data set: https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1614606248587000&usg=AOvVaw38ve7COMAl4g9GI3KAigob

## Summary of Findings

I found that: Loan amount shape is skewed-right with a peaks at 4000, 10000, 15000, 20000 and 25000 USD
and Monthly Income has a long tailed distribution with a few borrowers with high income and the peak at 4666 USD monthly, Less than that, approval of the loan will be difficult and as the income increase The need for a loan is decrease
 - there is three terms to pay 1 year and 3 years and 5 years the most prefer to pay Loan installments on 3 years and a few pay within one year
we can see if the borrower own a home or not, have a little influence on the numbers of loans. may be have more effect on the amount of the loan
- the most occubation of borrower is Proffessionl then coumputer programer then Executive then teacher an go on as at the chart
- We see that the most borrow the loan to consolidation there debit then the most need to improve there homes then busines then to the car and go on.
- I see that Borrowers are repaying well, not many clients are defaulting and very few loans have been canceled
- from loan date we can see the work is good start from 2006 then at 2008 because The global economic crisis the loans cound decreased until 2010 then the economy refresed till 2013 and a jump happened with 2014.
I expected more irregularity in payment than this! the Distribution of Listing Category need to explain the labels because it's written with coded numbers. Also there is borrower with monthly income 1,750,000 (I don't expect this is a error because no erros like that in mone and the next income is 6185,47) but No one expects the actions of businessmen.
There is no clear (linear) relationship between the monthly income and the amount of the loan as I expected because it is clear that loans in the United States are easy to adopt, unlike my place of residence, I can see that who have minimum income take more loans with the minimum amount and. Also the smalest values (low income, small loan) have a high density

Borrowers with lowest score can take a loans yes it's not like high score but also more than my expectation.

Contrary to my expectations, there are not a few 4,000 USD loans payable over three years
The borrower owns a home that qualifies him to receive a higher loan. Also employed status can get the hiest loan and full-time status have a 25000 limit with few exeptions and the not employed, retired, part-time, not avalable and self employment status has limit with 25000 USD without exeptions
Do not be surprised but I found that home ownership gives an opportunity for a bigger loan but less than I expect




## Key Insights for Presentation

Dataset is cleaning very well the one thing I did is explain the labels of Distribution of Listing Category because it's written with coded numbers.

I uset the codes wich written at project example here: https://video.udacity-data.com/topher/2018/August/5b7de78c_communicate-data-example-project/communicate-data-example-project.zip this helped me to code my ideas.# Data-visualization.
