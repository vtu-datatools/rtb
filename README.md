In BC and many provinces of Canada, a system exists for resolving
disputes between tenants and landlords. Under authority of the
Residential Tenancy Branch (RTB), tenants or landlords can enter what is
effectively arbitration to resolve disputes. A few months ago we
discovered that all the RTB disputes and their resolutions are put up
online in public. We then went ahead and downloaded all the ones we
could. This is what we have found so far.

### Important Caveat

Many issues between tenants and landlords never make it to the RTB
process. Many people don’t know it exists or how to use it. The process
can be cumbersome to use and there are filing deadlines people may not
know about. What we are seeing is only narrow slice of people in BC
effected by these problems.

### Summary of the data

Total number of reports: 124146

Total number of reports which list a company: 25481

Percent of reports which list a company: 20.53%

The RTB system was introduced in 2007, but it’s not until 2013 that
people seem to start using it.

![](rtb_note_files/figure-markdown_strict/unnamed-chunk-7-1.png)

In particular, property company names are not listed until 2013

![](rtb_note_files/figure-markdown_strict/unnamed-chunk-8-1.png)

So what are the companies that keep coming up in disputes?

![](rtb_note_files/figure-markdown_strict/unnamed-chunk-10-1.png)

    ## Total number of unique companies: 9046

Dispute Codes
-------------

Each case comes with a set of dispute codes to help categorize the
report. A natural question is ask is what codes occur the most often?

![](rtb_note_files/figure-markdown_strict/unnamed-chunk-13-1.png)

These codes can mean multiple things so side-by-side with their
descriptions, we see that most disputes are recovering costs from
repairs and pets.

<table>
<thead>
<tr class="header">
<th style="text-align: left;">Code</th>
<th style="text-align: right;">Frequency</th>
<th style="text-align: left;">Description</th>
<th style="text-align: left;">Category</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="text-align: left;">FF</td>
<td style="text-align: right;">11251</td>
<td style="text-align: left;">Recover filing fee from the other party</td>
<td style="text-align: left;">Application Process</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNR</td>
<td style="text-align: right;">9037</td>
<td style="text-align: left;">For unpaid rent or utilities</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MNR</td>
<td style="text-align: right;">9037</td>
<td style="text-align: left;">Monetary order for unpaid rent or utilities</td>
<td style="text-align: left;">Landlord filed for dispute resolution</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNR</td>
<td style="text-align: right;">9037</td>
<td style="text-align: left;">Recover cost of emergency repairs</td>
<td style="text-align: left;">Repairs or the Condition of the Rental Unit</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MNR</td>
<td style="text-align: right;">9037</td>
<td style="text-align: left;">Recover cost of emergency repairs</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="even">
<td style="text-align: left;">OPR</td>
<td style="text-align: right;">7382</td>
<td style="text-align: left;">Tenant has not paid the rent or utilities</td>
<td style="text-align: left;">End of Tenancy Notices</td>
</tr>
<tr class="odd">
<td style="text-align: left;">OPR</td>
<td style="text-align: right;">7382</td>
<td style="text-align: left;">Tenant has not paid rent or utilities</td>
<td style="text-align: left;">Landlord filed for dispute resolution</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNSD</td>
<td style="text-align: right;">6680</td>
<td style="text-align: left;">Keep all or part of pet damage deposit or security deposit</td>
<td style="text-align: left;">Security or Pet Deposit</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MNSD</td>
<td style="text-align: right;">6680</td>
<td style="text-align: left;">To keep all or part of pet damage deposit or security deposit</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNSD</td>
<td style="text-align: right;">6680</td>
<td style="text-align: left;">Return of all part of pet damage deposit or security deposit</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MNSD</td>
<td style="text-align: right;">6680</td>
<td style="text-align: left;">Return pet damage deposit or security deposit</td>
<td style="text-align: left;">Security or Pet Deposit</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNDC</td>
<td style="text-align: right;">5890</td>
<td style="text-align: left;">Owed or compensation for damage or loss under the Act, regulation or tenancy agreement</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MNDC</td>
<td style="text-align: right;">5890</td>
<td style="text-align: left;">Owed or compensation for damage or loss under the Act, regulation or tenancy agreement</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="even">
<td style="text-align: left;">MNDC</td>
<td style="text-align: right;">5890</td>
<td style="text-align: left;">Compensation for damage or loss under the Act, regulation or tenancy agreement</td>
<td style="text-align: left;">Repairs or the Condition of the Rental Unit</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CNC</td>
<td style="text-align: right;">3342</td>
<td style="text-align: left;">Cause</td>
<td style="text-align: left;">End of Tenancy Notices</td>
</tr>
<tr class="even">
<td style="text-align: left;">MND</td>
<td style="text-align: right;">2323</td>
<td style="text-align: left;">Recover cost of damage to the unit, site or property</td>
<td style="text-align: left;">Repairs or the Condition of the Rental Unit</td>
</tr>
<tr class="odd">
<td style="text-align: left;">MND</td>
<td style="text-align: right;">2323</td>
<td style="text-align: left;">For damage to the unit, site or property</td>
<td style="text-align: left;">Money or Monetary Orders</td>
</tr>
<tr class="even">
<td style="text-align: left;">CNR</td>
<td style="text-align: right;">1860</td>
<td style="text-align: left;">Unpaid rent</td>
<td style="text-align: left;">End of Tenancy Notices</td>
</tr>
<tr class="odd">
<td style="text-align: left;">CNR</td>
<td style="text-align: right;">1860</td>
<td style="text-align: left;">Cancel a notice to end tenancy relating to unpaid rent</td>
<td style="text-align: left;">Tenant filed for dispute resolution</td>
</tr>
<tr class="even">
<td style="text-align: left;">OLC</td>
<td style="text-align: right;">1702</td>
<td style="text-align: left;">Order to require a party to comply with the Act, regulation or tenancy agreement</td>
<td style="text-align: left;">Miscellaneous</td>
</tr>
</tbody>
</table>

Further work that’s needed
--------------------------

### Keyword analysis

This dataset includes free text that we have largely ignored. We can
really still drill down and ask. How many of these disputes involve
repairs as the main issue?

### Tracking which party wins disputes

While easy for a human being, it’s hard for tools to automatically
determine in whose favor was the judgement. It would be nice to find a
while to automatically determine this and surface it.
