# Simulating-Theater-Experience-SIMUL8

**Summary**
Created multiple simulation models on SIMUL8 software for a theater company to modify number of staff members, starting times, kiosks, and guest arrivals in order to maximize the number of customers as well as maximize profits for the theater.

**Details**
*Current Allocation*
For the current case allocation, Cascade on Broadway currently would have 1 staff member at the box office, 3 ushers, 2 bartenders and 1 worker for the bodega. With these 7 staff members, they would only manage to seat 463 viewers out of a possible 1475 before 8:05pm when the show starts which is less than a third of all customers. This means that over two-thirds of all customers would miss the first half of the show as they would not be allowed in until intermission. Additionally, this will lead to only 59 people attending the bar where the margins are the highest. This leads us to the conclusion that more staff members are needed in order to get everyone into the theatre before 8:05pm when the show begins.

*Base Model 1*
In order to determine how many staff members were needed at each station, we first observed the queues at each point of sale to determine where more staff members were needed until our simulation was able to get all 1475 patrons into the theatre. For the first model, we kept the opening time at 7:30pm for the queues until all the customers can purchase their tickets and start going into the theater. A solution of 8 staff members for box office, 9 ushers, 7 bartenders, and 1 bodega staff was devised through trial and error which was the least number of staff members needed to get all 1475 customers into the theater. Although this solution ensured that all customers got into the theater on time, it did not maximize profits since having more people go to the bar would lead to higher margins and profits. To devise a solution for this, we tackled each bottleneck on at a time by changing only one resource and keeping the rest of the staff members fixed. For instance, For the number of box office staff members, this meant that 8 workers would lead to the highest profits. For the ushers, box office was kept constant at 8 and we found that 12 ushers would lead to the highest profits, after which we would get diminishing returns. 

Lastly, 8 bar staff members maximized profits while keeping box office and ushers consistent at 8 and 12 workers respectively. Bodega staff members were kept at 1 since it was not a bottleneck in the process. This led to our final solution of employing 8 box office workers, 12 ushers, 8 bartenders, and 1 bodega worker for a total of 29 staff members leading to a maximized profit for the 7:30 opening time case being at $148,527 assuming each ticket costs $100 each.

*Early Start Time Model*
Next, we modified the model to include a 7:15 start time and repeated the same process from the previous base case. Opening the theater early led to the same number of box office employees at 8 workers, but it led to three less ushers at only 9 ushers working. 

The number of bar workers decreased as well to only 5 bartenders which meant that starting earlier gave more time for customers to space themselves out and not having to wait in lines for too long which means we only had to employ 23 workers, a grand total of 6 less workers as a result of opening up 15 minutes earlier. This also led to higher profits as more people attended the bar and we had less resources committed to employees.

*Complex Model*
Lastly, for the complex model that Bonnie described earlier, we added a self-serving kiosk machine at a price of $500 in addition to opening at 7:15pm to increase the rate of Willcall customers coming into the theater. By employing the same trial and error tactics from the previous two model simulations, we recognized that 4 box office staff members and 5 self-serving machines would optimize profits.

Additionally, 7 ushers and 5 bartenders gives us the maximized profits for our complex case scenario. Adding the machines means that we only employ 17 staff members along with having 5 machines to get the max profits for this scenario. This model has higher fixed costs but lower variable costs than all other models.

*Final Recommendation*
All 6 of our scenarios enable 1475 tickets to be sold and all customers to be within the theater for the start of the show. Scenarios 1, 3, and 5 correspond to opening the theater at 7:30, 7:15, and adding the machine complexity into the case with the intent of minimizing the number of staff members. Scenario 2, 4, 6 on the other hand correspond to opening the theater at 7:30, 7:15, and adding the machine complexity with the intent of maximizing profits for the theater. From this chart we can clearly see that having an early start time to the theater is the best case scenario for maximizing profits. This case involved hiring 8 box office works, 9 ushers, 5 bartenders, and 1 bodega worker for a total of 23 workers which led to the highest profits of any scenario with upwards of $149,000 in profits.
