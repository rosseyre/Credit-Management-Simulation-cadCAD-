# Mutual Credit: Designing Automated Credit Management logics using cadCAD

The model leverages the cadCAD python library to simulate user transactions in a mutual credit system. An automatic Credit Management algorithm adjusts the user's credit limit according to their spending/earning behaviour. Parameters such as 'integrity' adjust spending patters to assess how the Credit Management algorithm responds to differing user behaviour.

<i>Mutual Credit:</i> 
- In a mutual credit system, a user's balance may be either positive or negative, limited by their respective 'credit limit'. 
- The net balance of all accounts in a mutual credit system is zero, since each transaction has a corresponding debtor and creditor.

## Model purpose
Mutual credit systems require effective credit limit management to ensure equitable participation. Effectively, in a well functioning credit ecosystem, users should retain a net zero average balance over time, since this corresponds to equitable production and consumption of goods & services. The intention of this cadCAD model is to aid in the design of an automated credit management algorithm that could be utilised in a P2P mutual credit accounting system (built on Holochain, for example).

## Model scope & limitations

Since the model generates random incoming & outgoing transactions independent of the user's perception of their 'spending capacity', the model is useful insofar as it enables us to observe how the Credit Management algorithm responds in various circumstances. In other words, it is not an agent-based simulation where users might respond to the state of the system according to encoded logics. Instead, paramaters which adjust the relative 'weight' of incoming v.s outgoing transactions (nameley, 'integirty coefficient') are used to test how the Credit Management algorithm responds.


## Author
Ross Eyre is a transdisciplinary designer at Arkology, a design studio working at the intersection of Web 3 and sustainability - including alternative currency design and Commons-oriented P2P ecosystems.

System Dynamics and Agent-based modelling are applied 'systems thinking' tools, enabling deeper study and better design choices within the complex domain. Systems modelling is integral to the design of cryptoeconomic systems since they enable the evaluation of protocols and incentives prior to deployment.

<i>LinkedIn:</i>
https://www.linkedin.com/in/rosseyre/

<i>Twitter:</i>
https://twitter.com/rosseyre

## Links
Arkology: https://arkology.co.za <br>
cadCAD: https://cadcad.org/ <br>

## Plots
 
#### Demonstration of credit management (single user):
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/User%201%20-%20integ%201.png)

#### Demonstration of credit management (interactive slider effecting spending proclivity):
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/User%203%20-%20Integ%201.2.png)

#### Monte Carlo runs showing distribution of user balances over 10 simulations:
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/Monte%20Carlo%20Distribution%20(Integ%201).png)

#### Monte Carlo runs showing effect of decreasing users' spending proclivity:
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/Monte%20Carlo%20Distribution%203.png)

#### Matrix plot showing bell-shaped relationship (Credit Limit v.s. Avg Balance) for a single user:
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/Matrix%20plot%201.png)

#### Plot showing all simulations with paramater sweep over 3 values of 'Integrity Coefficient':
![alt text](https://github.com/rosseyre/CURRENTS-Credit-Management---cadCAD/blob/main/Images/All%20Runs.png)
