## Study 1: Gym Memberships

A health insurance company is thinking about paying for gym memberships for all their clients in the hopes that they will promote fitness and reduce healthcare costs (enough to offset the cost of the memberships).

To see if this would be worthwhile, they survey a random sample of their clients in the Durham, NC area about whether they currently have gym memberships.

They then correlate this data with the “fitness” of their members. (Let’s just talk about “fitness”, assuming they come up with some fancy index related to cholesterol, resting heart rate, and lots of other things that predict healthcare consumption and cost to the insurer).

They find that their clients with gym memberships are healthier than their clients without gym memberships.

**1.1 Define the outcome of interest**

>The outcome of this study is personal fitness which is associated with healthcare consumption and cost to the insurer.

**1.2 Define the treatment of interest**

> Owning a gym membership is the treatment.

**1.3 Give a reason that there may be baseline differences between groups**

> People who are owning gym membership may be wealthier than people who do not. And more affluent people are more likely to access healthier food, better medical resource, and more extended education. These factors are also associated with personal fitness.

**1.4 Give an example of how you could evaluate that possibility**

> If possible, I would include personal income into my survey to eliminate the economic difference's baseline differences. Suppose there is no significant income difference between the control group and the treatment group, then it is safe to say personal income would not bring baseline differences,  because high income will lead to better fitness. 

**1.5 Give a reason there may be differential treatment effects**

>Here is a possible reason that the treatment effect would fail. People who do not own gym membership may be too busy to go to the gym or just because they prefer to stay at home. If so, holding a gym membership would not persuade these people to go to the gym, let alone improving their fitness. 

**1.6 Give an example of how you could evaluate that possibility**

>To example the possible differential treatment effects mentioned in 1.5, here is a possible practice. Sometimes, history is a mirror to the future. To judge whether the willingness to go to the gym is a critical factor in preventing people from owning gym membership, I would find people owning gym membership last year but do not have it currently and mark them as a resigning group. Correspondently, the people who have gym membership last year and now would be marked as a keeping group. By comparing how many times they went to gyms previous year, we can determine the difference in fitness willingness between the two groups. 

## Study 2: Car Insurance

A car rental company currently offers renters two insurance options: a high deductible (but lower fee) option, and a low deductible (but higher fee) option.

(A “high deductible” insurance policy means that in the event of an accident, the renter is responsible for more out-of-pocket costs before insurance kicks in).

The rental car company has found that the people with the higher deductible insurance are less likely to get into accidents. (even with the higher deductible, they lose money on accidents given the hassle of getting new cars in their fleet).

With that in mind, it’s thinking of having all rental agreements use the “high deductible” insurance.

**2.1 Define the outcome of interest**

>In this case car accidents is the outcome of interest. 

**2.2 Define the treatment of interest**

> The treatment is high deductible insurance. 

**2.3 Give a reason that there may be baseline differences between groups**

> People who choose high deductible insurance may understand that they have better driving skills or driving manner, so they are less likely to encounter a car accident. 

**2.4 Give an example of how you could evaluate that possibility**

> We can compare renters' historical driving records. By doing so, we can figure out whether driving skills or driving manner are baseline differences between the two groups. 

**2.5 Give a reason there may be differential treatment effects**

>It is reasonable that high deductible insurance would warn renters to drive more carefully; in this case, the treatment effects will be apparent. However, there is another case that the treatment effect may not be noticeable. For example, people can expect that the treatment would not affect people who choose low deductible insurance because of their poor driving skills. 

**2.6 Give an example of how you could evaluate that possibility**

>We can collect last year's car accident number when people drive their own car from two groups and named the number OCAN (own car accident number ). Then we can select two subgroups that shares the same OCAN from the high deductible insurance group and low deductible insurance group. Since the two subgroups' OCAN are identical, we can expect no significant driving skills difference between the two groups. After that, we can compare the two subgroups' car accident numbers when driving rented cars and name the number as RCAN (rented car accident number ). The difference of RCAN would reflect treatment effect more reasonably. 



## Study 3: Billboard

You work for a Tesla dealership in Hillsboro (a town a little outside Durham, NC). You’ve heard that your colleagues who run a Tesla dealership near Duke Medical Center in central Durham have a billboard up. You also know that they sell substantially more Tesla’s than you.

So you’re thinking about also putting up a billboard near your store.



**3.1 Define the outcome of interest**

> The outcome of interest is sales of Tesla.

**3.2 Define the treatment of interest**

> The treatment of interest is to put a billboard up near my store.

**3.3 Give a reason that there may be baseline differences between groups**

> There may be baseline differences due to store locations. My store is located in a town outside Durham, while my colleagues' store is near Duke Medical Center in central Durham, which potentially attract more customers such as students and patients.

**3.4 Give an example of how you could evaluate that possibility**

> We could collect and compare the historical sales of two stores in the same period without a billboard. Then compute $E(Y_{0}|D = 0) = E(Y_{0}|D = 1)$ to evaluate that possibility. 

**3.5 Give a reason there may be differential treatment effects**

> Billboards are usually a good way to advertise for dealership in a town.

**3.6 Give an example of how you could evaluate that possibility**

> We could estimate $E(Y_{1}|D = 1) = E(Y_{0}|D = 0)$ to evaluate that possibility. 




