Download Link: https://assignmentchef.com/product/solved-vg441-homework-1
<br>
<strong>Problem 1</strong>

Prove that the derivative of <em>θ<sup>T</sup>X<sup>T</sup>Xθ </em>with respect to <em>θ </em>is 2<em>X<sup>T</sup>Xθ</em>.

<h1>Problem 2</h1>

<table width="434">

 <tbody>

  <tr>

   <td width="50"><strong>Age</strong></td>

   <td width="113"><strong>Home Owner</strong></td>

   <td width="98"><strong>Car Owner</strong></td>

   <td width="107"><strong>Having Kids</strong></td>

   <td width="66"><strong>Salary</strong></td>

  </tr>

  <tr>

   <td width="50">40</td>

   <td width="113">Yes</td>

   <td width="98">Yes</td>

   <td width="107">Yes</td>

   <td width="66">10000</td>

  </tr>

  <tr>

   <td width="50">20</td>

   <td width="113">No</td>

   <td width="98">No</td>

   <td width="107">No</td>

   <td width="66">500</td>

  </tr>

  <tr>

   <td width="50">50</td>

   <td width="113">Yes</td>

   <td width="98">No</td>

   <td width="107">Yes</td>

   <td width="66">8000</td>

  </tr>

  <tr>

   <td width="50">30</td>

   <td width="113">Yes</td>

   <td width="98">No</td>

   <td width="107">No</td>

   <td width="66">5000</td>

  </tr>

 </tbody>

</table>

<h2>Tasks</h2>

<ul>

 <li>Run GBM on paper for two iterations (i.e., stopping at F2 and PR2). No more than 4 leaves. Use learning rate <em>γ </em>= 0<em>.</em> Features can be re-used in DT.</li>

 <li>Run XGBoost on paper for two iterations (i.e., stopping at F2 and PR2). No more than 4 leaves.</li>

</ul>

Use regularizer <em>λ </em>= 1 and pruning <em>γ </em>= 0 and learning rate <em>µ </em>= 0<em>.</em>1.

<h1>Problem 3 (Open-Ended)</h1>

<h2>Dataset</h2>

California housing price data in the 1990-2000. 1–9 are the features and 10 is the target.

<ol>

 <li>longitude: A measure of how far west a house is; a higher value is farther west</li>

 <li>latitude: A measure of how far north a house is; a higher value is farther north</li>

 <li>housingMedianAge: Median age of a house within a block; a lower number is a newer building</li>

 <li>totalRooms: Total number of rooms within a block</li>

 <li>totalBedrooms: Total number of bedrooms within a block</li>

 <li>population: Total number of people residing within a block</li>

 <li>households: Total number of households, a group of people residing within a home unit, for a block</li>

 <li>medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)</li>

 <li>oceanProximity: Location of the house w.r.t ocean/sea</li>

 <li>medianHouseValue: Median house value for households within a block (measured in US Dollars)</li>

</ol>

<h2>Tasks</h2>

<ul>

 <li>Build a Linear Regression Model using 80% training set and 20% testing set. Interpret your results as much as you can.</li>

 <li>Build a GBM using 80% training set and 20% testing set. Interpret your results as much as you can.</li>

 <li>Build a XGBoost Model using 80% training set and 20% testing set. Interpret your results as much as you can.</li>

</ul>