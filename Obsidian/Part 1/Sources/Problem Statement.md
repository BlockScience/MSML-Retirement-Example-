## Problem Statement

For this guided example, the following is the problem statement from which we will build the specification.

Investing for retirement is often modeled with monte carlo simulations because of how much path dependence there is. The following are the specific facts of the problem:
- There is only one person of interest in the model, the [[Person|employee]] looking to retire.
- They [[TBD Allocation|only have control over the allocation percentages at any given time between bonds and stocks]]. This percentage will over time change, however, based on how the [[TBD Asset Price Change|prices of the assets change]]!
- Any time a trade is conducted, we can assume no comissions or fees, although the model could be enriched by adding this.
- The [[TBD Return Behavior|returns of both stocks and bonds are assumed to be randomly distributed]] (although this could of course be extended to get more accurate measures), and can be parameterized by $\mu_s$, $\sigma_s$, $\mu_b$ and $\sigma_b$.