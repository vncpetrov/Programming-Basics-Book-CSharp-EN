## Problem: Logistics

You are responsible for the logistics of different cargos. **Depending on the weight** of each load is needed **different vehicle** and costs **different price per tonne**:

 * Up to **3 tonnes** – **minibus** (200 BGN per tonne).
 * From **over 3 and up to 11 tonnes** – **truck** (175 BGN per tonne).
 * **Over 11 tonnes – train** (120 BGN per tonne).

Your task is to calculate **the average price per tonne of the cargo**, and also **how much percent of the cargo is transported in each vehicle** .

### Input Data

From the console is read **sequence of numbers**, each on separate line:
 * **First line**: **count of the cargos** for carriage – **integer number** in range [**1 … 1000**].
 * On the next lines is given **the tonnage of the current cargo** – **integer number** in range [**1 … 1000**].

### Output Data

Print on the console **4 lines**, as follows:
 * **Line #1** – **the average price per tonne of the cargo** (rounded to the second place after the decimal point).
 * **Line #2** – **percent** of the cargo, carried by **minibus** (between 0.00% and 100.00%, rounded to the second place after the decimal point).
 * **Line #3** – **percent** of the cargo, carried by **truck** (between 0.00% and 100.00%).
 * **Line #4** – **percent** of the cargo, carried by **train** (between 0.00% and 100.00%).
 
### Sample Input and Output

<table>
<thead>
<tr>
<th align="left"><strong>Input</strong></th>
<th align="left"><strong>Output</strong></th>
<th align="left"><strong>Explanations</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top">4<br>1<br>5<br>16<br>3</td>
<td valign="top">143.80<br>16.00%<br>20.00%<br>64.00%</td>
<td valign="top">
By <b>minibus</b> are transported two of the cargos <b>1</b> + <b>3</b>, total <b>4</b> tonnes.<br>
By <b>truck</b> is transportde one of the cargos: <b>5</b> tonnes.<br>
By <b>train</b> is transported one of the cargos: <b>16</b> tonnes.<br>
<b>Sum</b> of all cargos is: 1 + 5 + 16 + 3 = <b>25</b> tonnes.<br>
Percent of the cargo <b>by minibus</b>: 4/25*100 = <b>16.00%</b><br>
Percent of the cargo <b>by truck</b>: 5/25*100 = <b>20.00%</b><br>
Percent of the cargo <b>by train</b>: 16/25*100 = <b>64.00%</b><br>
<b>Average price</b> per tonne of carried cargo: (4 * 200 + 5 * 175 + 16 * 120) / 25 = <b>143.80</b>
</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left"><strong>Input</strong></th>
<th align="left"><strong>Output</strong></th>
<th align="left"><strong>Input</strong></th>
<th align="left"><strong>Output</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top">5<br>2<br>10<br>20<br>1<br>7</td>
<td valign="top">149.38<br>7.50%<br>42.50%<br>50.00%</td>
<td valign="top">4<br>53<br>7<br>56<br>999</td>
<td valign="top">120.35<br>0.00%<br>0.63%<br>99.37%</td>
</tr>
</tbody>
</table>