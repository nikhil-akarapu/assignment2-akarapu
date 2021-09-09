# assignment2-akarapu
# I want to explore new things.
# NIKHIL KUMAR AKARAPU  
###### Nashville

Nashville is known worldwide for country music

Nashville was the first city **nationwide** to be granted an **FM-broadcasting license**.

*** 
## directions from Maryville to Nashville
1. Drive to Kansas 
2. take a flight from Kansas to Nashville
3. Will reach Nashville

### Things to Carry
-Passport

-Electronic gadgets

-Valuables

-Flight Tickets

[AboutMe](/AboutMe.md)

### Information about Food and Drinks
this following table consists of food,location and price

| food              | location               | amount  |  
|-------------------|------------------------|---------|
|  chicken Biryani  | Alpha Cafe,Kansas      |  $23    |  
|  Mutton Pulusu    | Dawat,Sanjoe           | $29     |   
|  Fish Fry         | IndiaSpice,Chicago     | $25     |  
| Egg fried rice    |   Indian spice,Chicago | $10     |  

### Quotes

>Intelligence is the ability to adapt to change

*Stephen Hawking*

>Death is so terribly final, while life is full of possibilities

*Gorge R.R.Martin*


### code fencing 
In mathematics, the binomial coefficients are the positive integers that occur as coefficients in the binomial theorem. Commonly, a binomial coefficient is indexed by a pair of integers n ≥ k ≥ 0 and is written {\displaystyle {\tbinom {n}{k}}.}{\displaystyle {\tbinom {n}{k}}.} It is the coefficient of the xk term in the polynomial expansion of the binomial power (1 + x)n

[Introduction](https://en.wikipedia.org/wiki/Binomial_coefficient#:~:text=In%20mathematics%2C%20the%20binomial%20coefficients%20are%20the%20positive,%2B%20x%29n%2C%20and%20is%20given%20by%20the%20formula)


'''
const int maxn = ...;
int C[maxn + 1][maxn + 1];
C[0][0] = 1;
for (int n = 1; n <= maxn; ++n) {
    C[n][0] = C[n][n] = 1;
    for (int k = 1; k < n; ++k)
        C[n][k] = C[n - 1][k - 1] + C[n - 1][k];
}

'''

[Pascals Triangle](https://cp-algorithms.com/combinatorics/binomial-coefficients.html)



