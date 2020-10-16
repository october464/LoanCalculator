# Mortgage Loan Calculator
Dragon - Star Coder Challenge Team 1
Orlando Olmo (PM), Jonathan Green (Dev), Tony Beavers (Des)

Project Description
This coding challenge was designed to test our coding skills as well as our remote collaboration skills.

The application requirements include three input parameters:
 1- The amount of money loaned in USD (balance).
 2- The time over which the loan will be repaid in months (term).
 3- The percentage rate at which interest will accrue on the loan (rate).
 
 The application should provide the following information as output:
  1- The monthly payment schedule from first to last for the life of the loan.
  2- The payment amount.
  3- The amount of principla paid each month.
  4- The interest paid each month.
  5- The total interest paid to date.
  6- The remaining loan balance at the end of each month.
  
  Financial formulas to be used for this excercise are:
   1- Total monthly payment = (loan amount * (rate/1200) / (1 - (1 + rate/1200)exp.(-number of months).
   2- Remaining Balance = before the very first month equals the loan amount.
   3- Interest Payment = previous remaining balance * rate/1200.
   4- Principal Paymant = total monthly paymant - interest payment.
   5- At the end each month = Remaning Balace = Previous Remaining balance - principal payments.
   
   Specific software Criteria:
    1- Built with Javascript, HTML, CSS, and Bootstrap.
    2- Code must reside in a Github repo.
    3- Github has all team members as contributors.
    4- App must be published to netlify.
    5- JS Plugins and other JS libraries can be used.
    
    pb: OJO
    JuiceDev20
