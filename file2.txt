Data analysis/manipulation AWK

Linux-content --> data.csv file
i) print employeeName and TotalPay who has BasePay greater than 10,000/-

command -->> $ cat data.csv | awk '{if($7>10000)print$2$7}'

a)read data file from commadn line and extract rows which have Baseapay > 10,000 
command -->> $ cat data.csv | awk '{if($4>10000)print$0}'

b) print only emp name and TotalPay
command -->> $ cat data.csv |  awk '{print $2 $7}'

ii) Find aggregate TotalPay of employee whose job title is CAPTAIN
command -->> $ cat data.csv | grep CAPTAIN | awk '{sum+=$7}END{print sum}'

a) Extract rows have CAPTAIN in the coloumn job title
command -->> $ cat data.csv | grep CAPTAIN | awk '{print$0}'
b) Extract total pay and calculate the sum.
command -->> $ cat data.csv | awk '{sum+=$7}END{print sum}'




