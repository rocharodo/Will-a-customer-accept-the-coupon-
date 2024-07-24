# Will-a-customer-accept-the-coupon-
The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.
<div style="background-color: #f9fcff;background-image: linear-gradient(147deg, #f9fcff 0%, #dee4ea 74%);">
<h1>Observations</h1>
<ol>
    <li>Bar coupons not seem to be very popular among this population as only 41% of the population accepted the Bar coupon</li>
    <li>Based on this investigation, people that go to a bar more than once a month, have passengers that are not a kid and are not widowed seem to be the best candidates for accepting the coupons.
</li>
    <li>Age does not seem to be a deterministic factor as we can see people under the age of 30 have a very similar acceptance rate to those over the age of 25. Perhaps further investigation is needed as there is an overlap with age 26 as it is on both samples</li>
    <li>Drivers with a Kid(s) as a passenger seem to be less responsive to the coupons</li>
    <li>Those drivers that go to a bar more than once a month are keener to accept the coupon</li>
</ol>    
</div>

<div style="background-color: #fec84e;background-image: linear-gradient(315deg, #fec84e 0%, #ffdea8 74%);">
<h1>Comparison Table</h1>
<table style="background-color:white;">
    <thead style="backgroud-color:yellow">
    <tr>
        <td>coupon</td>
        <td>proportion of {COUPON} coupons were accepted</td>
        <td>acceptance rate between those who went to a {COUPON} 3 or fewer times a month to those who went more</td>
        <td>acceptance rate between drivers who go to a {COUPON} more than once a month and are over the age of 25 to the all others</td>
        <td>acceptance rate between drivers who go to a {COUPON} more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry</td>
        <td>Compare the acceptance rates between those drivers who:- go to a {COUPON} more than once a month, had passengers that were not a kid, and were not widowed</td>
        <td>go to a {COUPON} more than once a month and are under the age of 30</td>
        <td>go to cheap restaurants more than 4 times a month and income is less than 50K</td>
    </tr>
    <tr>
       <td></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
       <td><table><tbody><tr><td>0</td><td>1</td></tr></tbody></table></td>
    </tr>
    </thead>
    <tbody style="backgroud-color:yellow;color:blue;">
    <tr>
        <td>Bar</td>
        <td><table><tbody><tr><td>0.589985</td><td>0.410015</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.437948</td><td>0.562052</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.378466</td><td>0.621534</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.376894</td><td>0.623106</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.30976</td><td>0.69024</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.371919</td><td>0.628081</td></tr></tbody></table></td>
        <td><table><tbody><tr><td>0.406044</td><td>0.593956</td></tr></tbody></table></td>        
    </tr>
    </tbody>
</table>

<h4>Note: 0 Not Accepted, 1 Accepted</h4>    
</div>
