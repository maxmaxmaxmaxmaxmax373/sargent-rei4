# 10. United States Then, Europe Now

## Introduction

 I work in a macroeconomic tradition developed by John Muth, Robert E. Lucas, Jr., Edward C. Prescott, Finn Kydland, Nancy Stokey, and Neil Wallace.
 I use macroeconometric methods championed by Lars Peter Hansen and Christopher A. Sims. I interpret macroeconomic history in ways advanced by Irving Fisher, Milton Friedman, Anna Schwartz, and François Velde.[^1]$\!^,$[^2] To illustrate how these research
 traditions
 have shaped me, I tell how predicaments facing the European Union today remind me of constitutional decisions the United States faced not once, but twice.

 I begin with a simple expected present value model for government debt and explain how {cite:t}`HS1980` used rational expectations econometrics to render this model operational by deducing cross-equation
 restrictions that characterize how the value of a government's debt depends on statistical properties of the government's net-of-interest surplus. This econometric specification
 isolates essential determinants of the value of a country's debt or currency. The econometric theory leaves open who chooses the
all important statistical process for the government net-of-interest surplus. In democracies, voters choose. To understand more, we think about outcomes that emerge under alternative democratic political arrangements.

A case study illustrates how democracies have balanced conflicting interests. My case study is
 how the constitutions of the United States have influenced the government net-of-interest surplus process and therefore the value of government debt. I say constitutions, plural,
 because we Americans have tried two of them, first the Articles of Confederation that were ratified in 1781, and then the US Constitution
 that was ratified in 1788. Those constitutions embraced two very different visions of a good federal union.
 The first constitution was designed to please people who preferred a central government that would find it difficult to tax, spend, borrow, and regulate foreign trade. The second served opposite interests. The US framers abandoned a first constitution
 in favor of a second because they wanted to break the prevailing statistical process for the net-of-interest government surplus and replace it with another
 one that could service a bigger government debt.[^3] Exactly how and why they did that is enlightening: starting in 1789, they rearranged fiscal affairs first and then
 approached
 monetary arrangements as an afterthought.

 The fiscal institutions of the European Union today remind me of those in the United States under the Articles of Confederation.
The power to tax lies with member states.
 Unanimous consent by member states is required for many important EU-wide fiscal actions.

Some lessons from US history are these:

1. *The ability to borrow today depends on expectations about future revenues.* Without institutions that provide adequate revenue sources, governments may have neither the current revenue nor the ability, by issuing debt, to pledge future revenues when occasions demanding especially large public expenditures arise. The inability to issue debt comes from the fact that prospective debt holders rationally anticipate that the government will be constrained in its ability to raise enough revenues to service the debt. To provide public goods, even rare ones like surges of defense spending during wars, governments require the flexibility to tap adequate sources of revenue.

2. *Free-rider problems exist for subordinate governments vis-à-vis a central government.* Because there is a classic free-rider problem in paying for public goods, subordinate governments, like states in the United States or nations in the European Union, cannot be relied on voluntarily to provide revenue to the central government to pay for public goods. Each state has an incentive to refuse, hoping that other states will accept the burden.

3. *Good reputations can be costly to acquire.* In deciding whether or not to pay preexisting debts, governments have strong incentives to default. Their anticipations of default make prospective creditors reluctant to purchase debts in the first place. Governments therefore have incentives to earn reputations that they will pay off their debts in the future. Acquiring such a reputation can be costly because it might well require making apparently unnecessary payments to debts incurred before the current government took office. Compensating such historical debt holders can seem unjust to current taxpayers, but it may be necessary for the long-run health of a republic.

4. *It can help to sustain distinct reputations with different parties.* It is challenging for a government simultaneously to sustain distinct reputations with disparate parties. This challenge manifested itself when the US federal government struggled to confront British trade restrictions from 1790 to 1812 and in the early 1840s when it wanted its actions to send separate nuanced messages to foreign and domestic creditors as well as various state governments.

5. *Confused monetary-fiscal coordination creates costly uncertainties.* Fiscal and monetary policies are always coordinated and are always sustainable, even though they may be obscure. In the beginning, the United States coordinated them by adopting a commodity money standard and restricting states and banks' ability to create fiduciary monies. Other arrangements are possible. You can have a monetary union without having a fiscal union. You may want a fiscal union even though you don't want a monetary union. Obscure coordination arrangements increase uncertainty in markets and among ordinary citizens.

## The Math

A basic theory about how creditors value a government's debt starts with a sequence of one-period budget constraints
$ g_t + b_t = T_t + R^{-1} b_{t+1}, $
or

$$
b_t = s_t + R^{-1} b_{t+1},  t \geq 0,
$$

where $R > 1$ is the gross return on one-period inflation-indexed government debt, $b_t$ is the stock of one-period pure discount (zero coupon) inflation indexed bonds
 issued at $t-1$ and falling due in period $t$, and $g_t, T_t, s_t= T_t - g_t$ are government expenditures net of interest payments on the debt, total tax collections,
 and the government net-of-interest surplus, respectively.
Iterate the government budget constraints for $t \geq 0$ *backwards* to get

$$
b_t = - R[ s_{t-1} + R s_{t-2} + \cdots + R^{t-1} s_0] + R^t b_0 , t \geq 1,
$$

which states that large
government *debts* come from accumulating big government *deficits* $-s_{t-j}, j = 1, \ldots, t,$ as well as rolling over
any initial debt $b_0$.
 But to sustain large
government debts requires prospects of big government *surpluses* in the future. To appreciate this, iterate the budget constraints for $t \geq 0$ *forward* to get

$$
b_t = \sum_{j=0}^\infty R^{-j} s_{t+j},
$$

which states that the value of government debt equals the discounted present value of current and future government surpluses.
Recognizing that future surpluses can be forecast only imperfectly induces us to replace $s_{t+j}$ with $E_{t-1} s_{t+j}$, where $E_{t-1} (\cdot)$ temporarily denotes the public's forecast based on time $t-1$ information
known by prospective bond holders at time $t-1$ to be pertinent for forecasting future surpluses. (Remember that these one-period
bonds are purchased at time $t-1$ and redeemed at time $t$, so it is information at time $t-1$ that is pertinent for valuing bonds
that mature at $t$.)
Then the value of government debt becomes

$$
b_t =  \sum_{j=0}^\infty R^{-j} E_{t-1} s_{t+j} .
$$ (sarg1)

 To get practical implications from the bond pricing equation {eq}`sarg1` requires a theory about how people forecast the present discounted value of the government surpluses dedicated to servicing its debt.
In situations like this,
{cite:t}`HS1980` joined {cite:t}`Muth1960,Muth1961`, {cite:t}`Lucas_1972,Lucas_1976_Critique`, and {cite:t}`Lucas_Prescott_1971,Lucas_Prescott_1974` in applying the economist's venerable device of modeling decisions as optimization
problems.[^4] When the decision
is to choose a sequence of forecasts, this approach is said to impose *rational expectations*.[^5]
Evidently, *optimal* forecasts depend on the statistical properties of the object to be forecast.

 Suppose that the actual process for the government surplus is the first component of an $m \times 1$ vector
stochastic process $y_t$ that is governed by a moving average representation,
so that $s_t = e_s y_t$, where
$e_s$ is a selection vector and

$$
y_t = \sum_{j=0}^\infty C_j w_{t-j} ,
$$ (sargVAR1)

where $\{w_{t}\}$ is an $m$-dimensional martingale difference sequence and the information set $J_t$ known to prospective bond
holders at $t$ is generated by $w_t, w_{t-1}, \ldots$. Assume that $E w_t w_t' = I$.
Here $w_t$ constitutes “news” that arrives at time $t$. Following {cite:t}`HSR1991`, it is convenient to write the first equation of {eq}`sargVAR1` as

$$
s_t = \sum_{j=0}^\infty \sigma_j w_{t-j} = \sigma(L) w_t ,
$$ (sargVAR2)

where $L$ is the lag operator meaning $L^j w_t = w_{t-j}$ and $\sigma(L) = \sum_{j=0}^\infty \sigma_j L^j$.
Assume that the spectral density matrix $ S_y(\omega) = C(e^{-i \omega})  C(e^{i \omega})^T $ has full rank $m$ for almost all $\omega \in (-\pi, \pi)$, a condition equivalent with $y$
being stochastically nonsingular.[^6]

It is revealing and convenient to compute the value of bonds under rational expectations in two steps by applying an argument
that invokes the law of iterated expectations. First, temporarily give bond purchasers “too much” information by replacing the subjective expectation
$E_{t-1}( s_{t+j}) \equiv E (s_{t+j} | J_{t-1})$ in
equation {eq}`sarg1` with $E (s_{t+j} | J_t)$, the mathematical expectation of $s_{t+j}$ conditional
on the history of shocks $w_{t}, w_{t-1}, \ldots$ in equation {eq}`sargVAR1`. Under this expanded information assumption, {cite:t}`HS1980`
 showed in another context that[^7]

$$
b_t = \sum_{j=0}^\infty \kappa_j w_{t-j},
$$ (sarg2)

or

$$
b_t = \kappa(L) w_t,
$$

where

$$
\kappa(z) = \frac{ z \sigma(z) - R^{-1} \sigma(R^{-1} )}{z - R^{-1}},
$$ (sarg3)

where $z$ is a scalar complex variable and $\kappa(z)$ is the $z$-transform of the $\{\kappa_j\}$ sequence.[^8] Next, to
reduce information to the set $w_{t-1}, w_{t-2}, \ldots$ actually available to prospective bond holders when
they purchase the bonds at time $t-1$, we follow
{cite:t}`HSR1991` who establish that the requirement that $b_t$ be measurable with respect to time $t-1$ information $J_{t-1}$ information implies
that $\kappa_j= \kappa(0) =0$, which in light of equation {eq}`sarg3` requires that[^9]

$$
\sigma(R^{-1}) = 0 .
$$ (PVcoeff)

Equation {eq}`PVcoeff` has a natural economic interpretation: it states that the present value of the moving average coefficients for the net-of-interest
surplus must equal zero. This condition renders the value of debt maturing at $t$ measurable with respect to $J_{t-1}$.

Equations {eq}`sargVAR1`, {eq}`sargVAR2`, {eq}`sarg2`, {eq}`sarg3`, and {eq}`PVcoeff` encode cross-equation restrictions that are hallmarks of rational expectations econometrics: the coefficients $\kappa_j$ that tells the response of debt $b_t$ to past shocks $w_{t-j}$ are nonlinear functions of the discount factor $R^{-1}$ and the coefficients $\sigma_j$ in the moving
 average representation for the net-of-interest surplus $s_t$.[^10]

Equations {eq}`sargVAR1`, {eq}`sargVAR2`, {eq}`sarg2`, {eq}`sarg3`, and {eq}`PVcoeff`
illustrate much of the logical structure and empirical power of rational expectations econometrics:[^11]

- Current and lagged values of all components of the shock vector $w_t$ that impinge on future surpluses $s_{t+j}$ appear in the debt valuation equation {eq}`sarg2`.

- The shock response coefficients $\kappa_j$ in equation {eq}`sarg2` for the value of debt would change if government policy were permanently to alter the $\sigma_j$'s in {eq}`sargVAR2` that characterize the stochastic process for the government surplus. This technical finding is the heart of the influential critique of pre-rational expectations econometric evaluation procedures forcefully stated by {cite:t}`Lucas_1976_Critique`. I argue on page that George Washington and Alexander Hamilton understood that to increase the value of US government debt they would have to break the stochastic process {eq}`sargVAR2` for $\{s_t\}$ that had prevailed in the United States in the 1780s.

- The same basic theory applies when there are prospects for default. For example, in each period suppose that there is a probability $\pi \in (0,1)$ that the government will write off a fraction $\phi \in (0,1)$ of its debt.[^12] Let $\tilde R^{-1}$ be the discount factor applying to default-free debt. Then a “certainty equivalent” discount factor $R^{-1}$ that compensates a risk-neutral creditor for holding default-prone debt is

 $$
R^{-1} = \tilde R^{-1} \bigl[ (1-\pi) + \pi (1 - \phi) \bigr] .
$$ (eqn-Rdefault)

 With this adjustment to the discount factor, the preceding theory applies. Bigger haircuts $\phi$ and higher probabilities of default $\pi$ lower the discount factor $R^{-1}$ and thereby reduce the value of the debt.[^13]

- {cite:t}`HHLR2007` opened the way to extending the theory to incorporate variable discount factors that can absorb some of effects of the news shocks $w_t$.

- Important technicalities impede linking our theory to vector autoregressions. Shocks in vector autoregressions for $y_t$ must be in the Hilbert space spanned by $y_t, y_{t-1}, \ldots$ (see {cite:t}`Sims:1980`). These so-called “fundamental” shocks emerge from constructing the Wold moving average representation for $y_t$ that is associated with the limit of a sequence of finite order vector autoregressions as the lag length is driven to $+\infty$. {cite:t}`HSR1991` show that the internal logic of the present value equation {eq}`sarg1` and the associated restriction $\sigma(R^{-1}) = 0$ imply that the moving average {eq}`sargVAR1` is *not* a Wold representation because the shocks $w_t, w_{t-1}, \ldots$ span a larger space than the linear space spanned by $y_t, y_{t-1}, \ldots$, and so the $w_t$ shocks are *not* what would be recovered by running a vector autoregression. {cite:t}`HSR1991` discuss substantial implications of this fact for extracting econometrically testable implications from the theory.[^14]

### Need for More Economic Theory?

 This piece of economics-plus-statistical forecasting theory forms the essence of the pricing model used by
 prospective buyers and sellers of government debt.[^15]
 For the purposes of those buyers and sellers, it is enough to have a good
 fitting *statistical* model of the stochastic process {eq}`sargVAR2` governing the government surplus.

 But for other purposes, a statistical model alone is inadequate.
 The model formed by equations {eq}`sargVAR1`, {eq}`sargVAR2`, {eq}`sarg2`, {eq}`sarg3`, and {eq}`PVcoeff` is superficial because the government surplus process $\{s_t\}$ is itself the *outcome* of a political
decision process.[^16]
 The model summarizes but does not purport to *explain* the statistical properties of the surplus process {eq}`sargVAR1`–{eq}`sargVAR2` in terms of the balance of conflicting interests
 that actually created it.

Economic theory goes deeper by analyzing contending economic and political forces that actually produce a statistical regime. In economic theory, an agent is a constrained optimization problem. A model consists of a collection
of constrained optimization problems. Theories of general equilibrium,
games, and macroeconomics acquire power by deploying an equilibrium concept whose role is to organize
disparate choice problems by casting them within a coherent environment.[^17]
 In the presence of one or more large player—governments in this case—decisions of some agents typically impinge on the constraint sets of others, and therefore on their incentives to take subsequent decisions. In such cases, the statistical process that represents an equilibrium outcome emerges jointly with agents' beliefs about what would happen in situations that they never face. Beliefs about those
 events have important influences on outcomes that do happen.[^18]
{cite:t}`Chari_Kehoe_1990`, {cite:t}`Stokey_1991`, and {cite:t}`Bassetto2005` have explored and applied notions of equilibrium appropriate to situations where a large government interacts with many atomistic private agents.

 I won't *formally* use a single such model in the rest of this chapter. But broad insights from this *class* of models shape virtually everything I detect in the fiscal and monetary history of the United States.

### A Humbling Message?

 Macro models use the standard equilibrium concept to produce statistical processes for things like the government surplus as *outcomes*. This is a powerful method for “explaining” objects like
$\{s_t\}$. But the equilibrium concept can disable someone who proposes to improve outcomes. Why? Because the equilibrium already contains the best responses of all decision makers, including any government agents who inhabit the model.[^19]
 Assuming that an equilibrium that explained the historical data can also be expected to “work” in the future puts a model builder in the position of not being able to recommend changes in policy precisely *because* he has understood the forces
that have led policy makers to do what they do. The model builder's way of understanding them is to say that they were optimizing. And giving advice would imply that he thinks that they weren't optimizing or weren't well informed.[^20]$\!^,$[^21]

### Modeling Reforms

By an *environment*, economic theorists mean a list of agents, a specification of actions available to every agent,
a timing protocol telling who acts when, and an information flow telling what is known, and when and by whom it is known. Some changes in an environment can amount to changes in institutions, e.g., reassigning particular decisions to an independent central bank or assigning particular taxes exclusively to states or exclusively to a central government within a federal system. This concept of equilibrium ties our hands by asserting that if you want to change outcomes, like the government surplus process mentioned above, then you have to reform institutions, which can mean agreeing on a new constitution. This is subversive. Nevertheless, that is what economic theory
teaches. George Washington and Alexander Hamilton knew it and
 that is why they
led a *second* political revolution, this one against the Articles of Confederation.
They redesigned American institutions partly because they did not like the (equilibrium) $\{s_t\}$ process and the implied value of government
debt that the Articles of Confederation regime had fostered.

## The United States

Acknowledging that I lack anything approaching a complete model, but highly prejudiced by a *class* of equilibrium models, I now pursue an informal
pattern recognition exercise to organize historical events that occurred in the United States and that remind me of choices being faced now as Europe struggles to manage a common currency.[^22]

 I see the authors of the constitution in 1787 and the architects of our federal government's institutions and policies in 1790–92 to be wrestling with the implications
 of the government budget constraint {eq}`sarg1`, an equation that preoccupies both the United States and some European states today.[^23]

### Victorious but in Default

The United States emerged from the US war for independence in 1783 with
 big debts and a constitution that disabled the US central government. The Articles of Confederation established a Continental Congress and an executive weak beyond the sweetest dreams of a contemporary American advocate of small government.
 The Articles worked as intended to restrain the central government from taxing and spending. That outcome served the interests of some US citizens, but not of others. It was not good for
 the Continental Congress's creditors.
 The Continental Congress lacked powers adequate to service its substantial foreign and domestic debts. To levy taxes, the central government required unanimous consent of thirteen
 sovereign states.[^24] To finance the war, the Continental Congress had printed IOU's in the forms of non-interest-bearing paper money (“bills of credit”) as well as interest-bearing debt.[^25] So had each of the thirteen states. After the war, the states could levy taxes to service at least parts of their
 interest-bearing debts.[^26]
 The central government could not. It regularly pleaded for contributions from the states,
 with at most limited success.[^27]
 An outcome was that Continental debts traded at deep discounts
 and so did debts of many states. Paper currencies depreciated markedly.[^28] Deprived of tax revenues, the Continental Congress tried to roll over its maturing debt and to pay interest falling due by borrowing more.[^29] This became increasingly difficult as the 1780s unfolded. Ultimately, the Continental Congress stopped paying its creditors and watched interest payments in arrears grow in the form of new IOU's called indents.
Authority to levy tariffs, the most remunerative potential source of tax revenues, resided in the states. In 1781 and 1783, the Continental Congress asked the thirteen states to ratify amendments to the Articles of Confederation
 that would have allowed it to impose a Continental
import duty whose proceeds were to be devoted entirely to servicing the Continental debt. Each time, twelve states approved, but one state did
 not (Rhode Island the first time, New York the second), killing the amendments.[^30]

### Trade Policies

In the 1780s under the Articles of Confederation, the US had thirteen tariff policies and thirteen trade policies. The states' main trading partner, Great Britain, discriminated against American shipping and American goods. Britain had done less of that before the revolution,
but a foreseeable consequence of victory in the American Revolution was that the thirteen American states would be excluded from the British imperial trading system. Occasionally individual American states sought to retaliate against British discrimination, but their efforts were always undermined by neighboring states.[^31] The British could play one US state against another.

### Crisis and a Second Revolution

Milton Friedman said that countries confront problems only after
 they have become crises.
 In the 1780s, the huge interest-bearing debts and currencies that had been issued to finance the war set the stage for a prolonged fiscal crisis from the point of view of the government's creditors, if not its taxpayers. Measured at par (but not at the deeply discounted values then prevailing in the market), the ratio of Continental plus state debt to GDP stood at about 40%, a massive debt at a time when the government could raise at most only a small percentage of GDP in taxes. About 2/3 of this debt had been incurred by the Continental Congress, the rest by the
 thirteen states.[^32]
 Sometimes *fiscal* crises have provoked political revolutions that renegotiate past promises and resettle accounts among taxpayers and government
 creditors, as they did in France in 1789 and the United States in 1787–88.[^33]

## Restructuring Fiscal Institutions

 To rearrange powers and incentives, the framers scrapped the original constitution, the Articles of Confederation, and wrote an entirely new one better designed to protect US government creditors.[^34]
 The US Constitution realigned incentives and authorities in ways that (a) let the central government devote enough tax revenues to service debts that the Continental Congress and the
 states had issued to pay for the war, and (b) gave the central government exclusive authority to tax and regulate US international trade. That gave the federal government the tools to implement a national trade policy that could deter British
 discrimination against US citizens.

 In the early days of the United States, the government budget constraint linked debt service capacity very closely to trade policy.
 That tariffs were the main source of federal revenues confronted the country with a choice that framed US politics from 1789 to 1815.
 Britain was the main potential trading partner of the United States. Raising revenues to fund US debt required sizeable and reliable trade volumes with Britain, even if that meant restraining US reactions to British discrimination against
 US goods and ships. But because they put a high priority on faithfully servicing the US government's debt and thereby earning the United States a reputation for paying its bills, Washington and Hamilton and the Federalists made preserving a difficult peace with Britain a cornerstone of their policy. So they refrained from retaliating against British trade restrictions. Later, because they wanted to retaliate against British trade restrictions,
 Jefferson and Madison and the Republicans were willing to imperil trade volumes with Britain and to sacrifice federal tariff revenues. They were willing to do that even if it affected US creditors adversely. {cite:t}`Irwin2009` describes how choices about these trade-offs can explain political outcomes in the United States both in the 1790s when the Federalists protected trade and peace and also after 1805 when the Republicans jeopardized trade and peace first with an embargo and then with
 the War of 1812 against Britain.[^35]

### The Order of Fiscal and Monetary Reorganizations

Hamilton and the first Congress reorganized fiscal affairs first.[^36]

### Fiscal Policy

Dates reflect priorities. Congress created the Treasury department on September 2, 1789, a Bank of the United States on February 25, 1791, and a US mint in the Coinage Act of April 2 1792.
 On September 21, 1789, the Congress directed newly appointed Secretary
of Treasury Alexander Hamilton to prepare a plan for “an adequate provision for the public credit.” Hamilton delivered his *Report on Public Credit* to Congress on January 14, 1790. Congress accepted Hamilton's recommendations, including his proposal to nationalize the states' debts,
 in the
 acts of August 4 and August 5, 1790.[^37]
 Those acts set out a detailed plan for rescheduling Continental debt by selling a set of securities that Congress designed with Hamilton's advice.
 These new debts promised to pay specific sequences of payoffs denominated in a unit of currency called a “dollar,” which in August 1790 was a silver coin issued by Spain.

{cite:t}`Hamilton_Credit`
told Congress that honoring the Continental Congress's original promises to pay would drive down *prospective* returns on government debt by raising
 *ex post* returns relative to what had been expected during the 1780s when Continental debt had traded at deep discounts.[^38] He
 also argued that prospective returns could be lowered if private traders would come to regard government debt as a fully trusted obligation to the bearer, increasing its liquidity.
 Confirming Hamilton's expectations, discounts on Continental and state bonds evaporated when news about the pro-administration outcome of the debate spread.[^39]

### Discrimination and Liquidity

An
especially fascinating part of Hamilton's report is his response to
James Madison's proposal to discriminate among current owners of Continental bonds according to when they had purchased
them.[^40]
 Motivated by concerns about fairness, Madison wanted to take away inordinate capital gains from people who
had purchased Continental bonds at discount; he also wanted to compensate former owners who had sold them at discount.
 Hamilton convinced Congress that such *ex post* discrimination would adversely affect the beliefs of
*prospective* purchasers of government debt and would thereby
 damage liquidity and trust in the market for bearer government bonds.[^41]$\!^,$[^42]

### Federal Bailout of States

The United States began with a comprehensive bailout of the individual states when on August 4, 1790 the US Congress accepted Alexander Hamilton's proposal to nationalize (or “assume”) states' debts. That completed a negotiation begun at the Constitutional convention when authority to tax imports had been transferred from the states to the federal government. In exchange for acquiring that most important revenue source, the federal government agreed to bail out the states, a decision that realigned creditors' interests
 away from states and toward the federal government.[^43] By converting creditors of the states into creditors of the central government,
 Hamilton converted those bond holders into advocates of a federal fiscal policy that devoted a substantial share of the proceeds of a revenue-raising tariff to servicing those bonds. A stated justification for nationalizing the states' debts was that most of them had been incurred to finance states' contributions to the national war for independence.
 The US Treasury set up a system designed to account for each state's contributions
 to the Glorious Cause and to compensate them accordingly. It would have been prudent for subsequent lenders to appreciate that Congress had
 reasoned that it was states' contribution to that national enterprise

 that justified the 1790 bailout. Investors should not have interpreted it as a promise to bail out states in the future no matter what, but apparently some of them did, to their eventual
 regret (please see the section “Another Federal Bailout of the States?” below).

### Why Pay?

The government institutions that they designed and the decisions that Congress and the president took in 1790 and 1791 confirm that the framers intended fully to honor the debts that they had inherited from the Continental Congress.
 Making good on the promises originally made to Continental and state debt holders to finance the US War of Independence meant disappointing other expectations and breaking promises at least implicitly
 made about other dimensions of fiscal policy, for example, to keep taxes low. The deep discounts at which Continental debts traded in the mid-1780s reflected traders' anticipations of those low-tax policies. Why, then, did the framers choose to keep some promises (ones to its creditors that had apparently already been substantially discounted) by
 breaking other promises (those to Continental taxpayers) that had been protected by the Articles of Confederation?[^44] If, as seems appropriate, we regard 1787 or 1789 as a new beginning —“time 0” in models of Ramsey plans and recursive mechanism design—then Ramsey models in the representative agent tradition of {cite:t}`Lucas/Stokey:1983`, {cite:t}`CCK`, and {cite:t}`Jones_Manuelli_Rossi` won't help us to answer that question. Those models typically advise a government to *default* on all initial public debts[^45] and thereby impose that least distorting of taxes, an unforeseen capital levy. Other revolutionaries have done that,[^46] but not the US framers. Their purpose in realigning authorities and interests
 was to affirm that a “deal is a deal,” at least so far as concerned obligations to the government's creditors, if not to taxpayers.

To understand why Hamilton and Washington and other framers wanted to pay, we have to take into account heterogeneities of economic situations and consequent conflicting interests[^47] as well as reputational considerations that are absent from these Ramsey models. The *purposes* for which those
 initial debt were incurred, the identities of the individual creditors, and the perceived adverse consequences of default all mattered in ways
 neglected at least by the three representative agent Ramsey models cited above.[^48] Such Ramsey models help explain government policies after some political revolutions,
 but not those of the United States in 1789.

In paying those Continental and state obligations,
 Secretary of Treasury Hamilton wanted the federal government to gain enduring access to
domestic and international credit markets. That would expand options for financing temporary surges in government expenditures
 by borrowing, thereby allowing his successors to moderate the contemporary tax increases needed to finance those surges.[^49] He also asserted that an outstanding stock of government debt earning a relatively risk-free
 return would foster the development of domestic credit markets, which he thought would be a boon to commerce and
 industry.[^50]$\!^,$[^51]

### Monetary Arrangements

Only after fiscal policy had been set on course in the acts of August 4 and August 5, 1790 did Hamilton and the Congress then turn to monetary policy.
Hamilton presented his *Report* proposing a Bank of the United States on December 14, 1790 and his *Report* proposing that the United States mint US silver and gold coins only on January 28, 1791. It was widely presumed that the United States would follow leading European countries in embracing
 a commodity money standard. So
the remaining monetary policy decisions for the framers simply involved choices of coin sizes and of a seigniorage rate for the mint.[^52]

### A National Bank?

After a tense debate during which James Madison argued that a federally chartered monopoly bank would be unconstitutional, the Congress awarded an exclusive 20-year federal charter to a Bank of the United States.[^53]
The bank was mostly privately owned and mostly operated in the interests of its private shareholders, though it did serve as fiscal agent of the federal government and as a depository for federal revenues. It also issued bank notes that circulated as currency and were convertible into specie on demand. It issued notes only in exchange for short term loans to the federal government or very short term commercial loans promising low risk. It avoided real estate and other long term and risky loans.
In these ways, it could be said to implement the “real bills” regime of Adam {cite:t}`Smith1806`, whose writings on the subject very probably influenced Hamilton.[^54]

### A Mint

The framers seem to have regarded monetary policy as a side show to be tidied up only after a sound fiscal policy had been secured.
The act of August 4, 1790 (1 Statutes, 138) had prescribed detailed procedures for funding US
and states' debts.
New federal IOU's were to be denominated in “dollars,” which on August 4, 1790 meant *Spanish* dollars because at that time there were no US dollars. In a report on coinage delivered in May 1791,
Hamilton proposed that the United States manufacture a silver dollar defined to have the same silver content as a Spanish dollar.[^55] The Mint Act of April 2, 1792 accepted Hamilton's recommendations virtually intact by creating a US dollar. In terms of the fundamental determinant of its value, namely, its metal content, the US dollar was a copy of the Spanish dollar, the only difference being that it had American and not Spanish “advertisements” stamped on its sides. In terms of essential economic forces, whether or not the United States actually issued these dollars
was incidental.[^56]

### Outcomes

 The Appendix to this chapter displays important outcomes in graphs of data taken mostly from early reports of the United States Treasury.
Deep discounts on the Continental debt evaporated and the federal government successfully rescheduled its debt (again see equation {eq}`eqn-Rdefault` for the discount factor).
 Tariffs comprised virtually all federal revenues. About 2% of GDP was collected in federal taxes annually during the 1790s. About 40% of those revenues were used to service the debt. Under Hamilton and
his Federalist successors, the debt was serviced and the principal rolled over, but substantial economic growth allowed the debt/GDP ratio to decline more or less continuously until the War of 1812, except for an increment used to finance
some of the 15 million dollars paid to Napoleon Bonaparte for Louisiana.[^57] In 1790, a big “fiscal space” (see {cite:t}`Ostry`) for the United States was provided
by prospects for rapid population and economic growth, prospects that were realized in the
25 years after 1790.

## Following Through?

 Timing protocols that prevail in a democratic society open enduring issues about the roles of commitments, precedents, and reputations.
 Expectations about *future* governments' decisions influence prices and quantities *today*, but today's citizens and policy makers
 cannot bind future citizens to prescribed
 courses of action.[^58] Decisions made in 1790 and 1791 were just the beginning of the great American fiscal and monetary adventure.
 Conjectures about how their successors would complete or modify their plans vitally concerned
 the framers.[^59]
 They had sought to create institutions (timing protocols?) and precedents (reputations?) that they hoped would limit subsequent
 choices in ways that would induce their successors to choose good public policies. Subsequent US history witnessed tax revolts
 (an armed rebellion against the federal government in 1794 western Pennsylvania when farmers
 protested a federal excise tax on whisky) and tariff and trade regulation revolts (in 1814 when New England states threatened
 to dissolve the union, and in the early
 1830s when President Jackson faced down John C. Calhoun and South Carolina during the nullification crisis). Struggles over
 how much the federal government should tax and spend and regulate continued until the US Civil War and beyond.

It is useful at this point to mention examples of how an administration's decisions interacted with those of its predecessors and those of its successors.

### Federal and State Paper Monies?

 The authors of the Constitution and
their supporters abhorred paper money and the sorry state to which American domestic, if not foreign, credit had been reduced.
That attitude set the stage for a
debate at the constitutional convention about which powers over monetary standards to assign to state and federal governments, and which to deny them.
Delegates to the convention agreed to prohibit *state*
governments from issuing bills of credit or otherwise make a paper currency a legal tender.[^60]
 What about the *federal* government?
Preliminary drafts of the constitution had given the federal Congress the right to issue bills of credit.
Thus, even though the Convention had already agreed explicitly to forbid states from issuing paper money, on the morning of August 16, 1787, the eighth clause of the seventh article in the draft of the constitution said
that “The legislature of the United States shall have the power to borrow money and emit bills on the credit of the United States.” Madison's notes of the convention's proceedings on August 16, 1787 record
 a debate about a motion to strike out the clause authorizing congress to emit bills of credit. The motion carried 9 states to 2.

Three contributions to the August 16 debate especially fascinate me.
(1) James Wilson's clear statements stressing the *ex ante* advantages in terms of promoting credit to be reaped by denying future government decision makers the authority to take actions
that would occasionally tempt them *ex post*;
(2) George Mason's and Edmund
 Randolph's statements urging the convention to appreciate the advantages of reserving for
 future decision makers enough flexibility to deal with contingencies of a kind that could not be
foreseen in 1787; and (3) Madison's remark that withholding the authority to make government
bills of credit legal tender would be sufficient to restrain potential abuses.[^61]$\!^,$[^62]

 Partly influenced by their understanding of that August 16, 1787 debate, during the first three quarters of the nineteenth century, many Americans believed that the framers had intended to shut the door on the federal government's issuing
a paper legal tender, and that the fact that the majority of the delegates did not go further and
 explicitly *prohibit* the federal government from issuing bills
of credit simply reflected the constitutional convention delegates' presumption that powers not explicitly awarded should be understood to be denied to
Congress.[^63]
An extensive review of the documentary record convinced
{cite:t}`Bancroft1886` that the framers' intent was clearly not to allow
 Congress to make a paper currency a legal tender.[^64]

### What Kind of Currency Union?

Before 1789, the thirteen states already had joined a currency union. All used the Spanish dollar.
 Article 1, section 8 of the US Constitution gives the federal Congress the exclusive power

> To coin Money, regulate the Value thereof, and of foreign Coin, and fix the Standard of Weights and Measures; $\ldots$

As we saw in the preceding section, the Constitution expressly prohibited states from issuing paper currency, and most believed that prohibition extended to the federal government.
 The federal government only modestly and temporarily[^65] circumvented that implicit limitation by allowing the
Bank of the United States to issue circulating notes in exchange for short-term government debts. It took longer for the states to circumvent the restriction.[^66]
In January 1837, in *Briscoe v. Bank of Kentucky*, the majority of the US Supreme Court, including newly appointed Chief Justice Taney,
 decided that state chartered and state owned banks had the right to issue paper bank notes (see {cite:t}`Howe`, ch. 11). The real bills reasoning of Adam {cite:t}`Smith1806` and {cite:t}`Sargent_Wallace_1982` or the Modigliani-Miller reasoning of {cite:t}`WallaceAER1981` indicates how this decision effectively disarmed the Article 1, section 10 prohibition against states' issuing bills of credit by allowing state banks to purchase state bonds with their circulating bank notes. After that and until Congress taxed them out of existence
 during the Civil War, a multitude of currencies circulated within and across states during what has been mislabeled a “free banking era.”[^67] Many such currencies circulated simultaneously with fluctuating rates of exchange that reflected
 probabilities that state chartered bank notes could be converted on demand into specie. So before
the US Civil War from 1861 to 1865, we had a currency union in one sense—the precious metals were the unit of account throughout the union;
but in another sense we did not—we had multiple currencies that presented citizens with choices about holding currencies
bearing different risks and returns. There was
no lender of last resort, no deposit insurance, and no presumption of federal bailouts of banks' depositors. All that stood behind those
notes was the prudence of bank managers promoted by what {cite:t}`Bagehot1920` called the “preservative apprehension” of owners of bank notes.[^68]

So if the framers intended to establish a *currency* union, they had at best mixed success, at least before the Civil War. And if they had wanted a currency union, it apparently would have been based on a commodity money, not a managed fiat currency like the one we have in the United States today.

 We now turn to continuing controversies about the scope of the *fiscal* union that
the framers established in August 1790.

## What Kind of Fiscal Union?

From the start of the republic in 1789 until the Civil War, Americans continued to dispute the proper scope and magnitude of federal tax, spend, transfer, and regulation
policies. Interests that coalesced around the great Whig statesman Henry Clay's American System in the 1830s advocated federal expenditures on infrastructure projects—roads, canals, railroads, universities—public goods that they argued merited national fiscal support. A coalition
of interests with strong support in the southern states blocked most such measures.[^69]
{cite:t}`McPherson`, Sec. III, ch. 14 documents how the 37th Congress (1861–62) seized the occasion of the secession of most slave states
to reorder the federal union along lines that fulfilled many of Clay's goals. On July 1, 1862 the Congress passed the Internal Revenue Act, which among other things imposed the first federal
income tax. On that same day, the Congress passed the Pacific Railroad Act awarding public lands and federal loans to companies that would construct
 intercontinental railroads. On July 2, 1862, Congress passed the Morrill Act awarding grants of federal land for establishing
 what came to be known as land grant colleges.[^70]
 Earlier, similar legislation had been defeated by a Democratic Party, now decimated by the loss of its core to the Confederacy, that had
 wanted a weaker federal union than Clay and Lincoln. The seceding states expressed those preferences when they wrote
 a Confederate Constitution that in important ways more closely resembled the Articles of Confederation than the US Constitution. It took
 four years of awful civil war to force rebels to accept not only Abraham Lincoln's interpretation of what it meant for all men to have been “created
 equal” but also the type of federal union that Hamilton and Washington had begun and that Abraham Lincoln preserved and extended.

### Another Federal Bailout of the States?

A sequel to Hamilton's 1790 bailout of the states' debts provides another example of how fiscal crises can provoke
enduring institutional changes, this time at the level of individual states.[^71]
Today, many US state constitutions require state governments to balance their budgets annually.
Before the 1840s, state constitutions of US states did not impose year-by-year balanced budgets. {cite:t}`Adams1887` tells how,
in response to adverse fiscal occurrences in the late 1830s and early 1840s, many states rewrote their constitutions to require
 balanced budgets annually.[^72] Here is the story.

During the 30 years after 1789, citizens debated whether the federal government should or could finance public infrastructure projects. Before the Civil War, they decided that it
couldn't. In response to
a string of presidential vetoes of public works appropriations, state governments assumed responsibility for public works projects. After 1829,
many state governments ran large government deficits, substantial parts of
which were justified at the time because they were said to be deficits on capital account, not current account. The logic was that those state bonds
had been issued to help finance public or private infrastructure projects. People advanced the theory
 that those bonds would be self-financing because ultimately they would promote growth and larger state government tax receipts in the forms of fees or taxes on increased land values.
Belief in that theory allowed state bonds
to be sold widely. Some were purchased by Europeans who were partly convinced by the self-finance theory and who also apparently mistakenly understood them to carry as much
investor protection as federal bonds, which had earned a good reputation through a sustained record
of having been honored after the Wars of Independence and 1812.
 And investors in state bonds knew that the federal government *had* comprehensively bailed out state debts at the beginning of
the republic. Also, Article 4, section 1 of the US Constitution mandates strong protection for owners of state debts:

> Full Faith and Credit shall be given in each State to the public Acts, Records, and judicial Proceedings of every other State. And the Congress may by general Laws prescribe the Manner in which such Acts, Records and Proceedings shall be proved, and the Effect thereof.

But foreign investors in state bonds may not have noticed weakened investor protection created by the
 Eleventh Amendment to the Constitution, passed in 1793
after a citizen of one state had taken a grievance against another state into a federal court. The Eleventh Amendment disarms the investor
protection originally guaranteed by Article 1, section 1 by stating:

> The Judicial power of the United States shall not be construed to extend to any suit in law or equity, commenced or prosecuted against one of the United States by Citizens of another State, or by Citizens or Subjects of any Foreign State.

For European and other bond holders, the story did not end happily. During a recession at the end of the 1830s,
many states defaulted.[^73] European bond holders then learned that the Eleventh Amendment deprived them and other creditors of American states of protection in federal courts. During the 1840s, Congress debated but ultimately rejected proposals for the federal government
to pay those state debts. During the congressional debates, advocates of a bailout recited the precedent set by Hamilton's 1790 bailout of the states. But opponents successfully argued that
Hamilton had bailed out state debts incurred for a glorious national purpose, while the debts of the early 1840s had been incurred for disparate causes to finance local projects. That and other arguments
 led Congress to refuse to bail out the state debts.

This episode cost the United States a hard-earned high-quality reputation for all US government debt, federal as well as state, and cast long reputational shadows
in two directions.
It seems that the international bond markets' response to these state bond failures
did not immediately include an inclination to adopt a nuanced view that discriminated finely between the credit worthiness of federal and state authorities. For years, the reputation of federal credit in Europe suffered along with
that of the states.

But the Congress's decision not to bail out the states had other, arguably more beneficial consequences for the country.
A legacy of the Congress's decision was that in the 1840s more than half of the US states rewrote their state constitutions
to require year-by-year balanced budgets. This is yet another example of fiscal crises that have produced the
lasting institutional changes that we sometimes call revolutions.[^74]$\!^,$[^75]

Did the Congress do the right thing in refusing to assume those state debts? There is a strong case to be made that it did: at the cost of temporarily sacrificing the *federal* government's hard earned good reputation with international creditors who were unable or unwilling to distinguish between
 the repayment records of federal and state governments, that decision succeeded in establishing a strong reputation of the federal government vis a vis the states. The Congress told the states not to expect the federal government to backstop their profligacy.[^76]
 To put the point bluntly, if by bailing out those state debts the federal government had set up expectations that they would back up state loans
 in the future, that would have exposed the United States to adverse consequences like ones that {cite:t}`KW` warned about in another context, namely, the insurance of financial institutions. {cite:author}`KW` taught that under-priced government insurance of deposits of inadequately regulated financial intermediaries provides incentives for those intermediaries to become as big as possible and as risky as possible. That will almost surely
 put the government into the position of eventually having to bail them out. Therefore, {cite:author}`KW` said that if you want to extend deposit insurance,
 you had better regulate financial intermediaries' portfolios. Extending and applying the {cite:author}`KW` logic to federal bailout of states, in exchange
 for offering such insurance, a federal
 bailout of the states would have set the United States on the road to extended federal control of states' fiscal policies. And where would that have ended? With federal control of cities too?[^77] Without Congress's 1840s refusal to bail out the states, it is probable that those state constitutions
 would never have been rewritten to mandate year-by-year balanced budgets.

## Lessons for Now?

 For the type of government we had under the Articles of Confederation in the 1780s—a weak fiscal union unlikely to pay its creditors what they had been promised—those deeply discounted Continental bonds had been fairly priced in the 1780s. Hamilton and Washington had set out to change the government's “type” by realigning interests
 in ways that would induce
 the United States to pay what it had promised earlier and would promise later. And Hamilton wanted the market to price the bonds accordingly (via formula {eq}`eqn-Rdefault` for the discount factor again). Hamilton set out to manipulate current and prospective public creditors' expectations about whether the government would honor its bonds the only way he knew: by creating a fiscal union with institutions and interests aligned in ways that would increase the *actual* probability
 that the federal government would pay. The framers' purpose in creating that fiscal union was not primarily to facilitate a monetary union, a distinct project about which they revealed substantial ambivalence in their subsequent indecision about whether to charter a national bank or whether instead to foster competition among private currencies
 issued by state chartered banks.

In terms of fiscal arrangements, the European Union today has features reminiscent of the United States under the Articles of Confederation.
The power to tax lies with the member states.
 Unanimous consent by member states is required for many important EU-wide fiscal actions.
 Reformers in Europe today seek to redesign these aspects of European institutions, but so far the temporal order in which
 they have sought to rearrange institutions has evidently differed from early US experience in key respects. The United States nationalized fiscal policy first, and
 for the US framers, monetary policy did not mean managing a common fiat currency, or maybe even having a common currency at all.
 The European Union has first sought to centralize arrangements for managing a common fiat currency and until now has not wanted a fiscal union. And to begin its fiscal union, the United States carried out a comprehensive bailout of the
government debts of the individual states. So far, at least, the European Union does not have a fiscal union, and few statesmen now openly call for a
comprehensive bailout by the European Union of the debts owed by governments of the member states.

Especially because of the contentious and obscure state of politics influencing monetary and fiscal policy in the United States today, an American is certainly not qualified to advise European citizens about what lessons, if any, to draw from the story about how the United States created a fiscal union. To ferret out useful lessons, it would be important to
identify circumstances in Europe now that match those of the United States then, and circumstances that differ.
The United States created its fiscal union at a time when the vast majority of people worked and lived on farms and when a substantial minority
were slaves. People were much poorer then than now. Life expectancies were so very much shorter then than now that few working people lived long enough or ever earned enough to be able to stop working much before they died. Doctors and medicine often did more harm than good, so it was probably better
that most people could not afford them. Deferred compensations, mostly
for military service (pensions) but also some for land confiscated from Native Americans, were the only legal entitlements to government-financed transfer payments. Most people could not vote. The federal government was small and it redistributed only a small fraction of GDP.
In peacetime in the first two decades of the United States , federal expenditures averaged 1 or 2 percent of GDP and in the beginning in the 1790s the federal
government allocated 40% of its tax revenues to servicing the federal debt.
The government debt that the Congress and president nationalized in 1790 had been incurred for a widely endorsed national cause.[^78] And fifty years later
when Congress refused another massive federal bailout of state debts, its actions proved that the *purpose* for which those state debts had been incurred mattered.

 Many of these circumstances differ in Europe today. Unlike the central government of the United States then, the European Union itself does not have a large debt; instead, the troublesome debts that the market discounts are
 all obligations incurred by subordinate governments. People live longer, and most do not work on farms. They retire for substantial periods of their lives, and many do not start working until much later
 in their lives than those early Americans did. There are large public expenditures on education. Medicines and doctors make people healthier and older.
Families are weaker. Government-financed safety nets and retirement and medical systems are pervasive and absorb substantial fractions of national budgets. Government regulations of
labor markets have changed —slavery is gone; there are minimum wages, unemployment and disability compensation arrangements, and
employment protection laws. These differ in their generosity and strength across EU states.[^79]
Are there greater differences in these institutions and people's skills and preferences across EU member states today than there were
in the United States then? In some ways, US member states were much *more* diverse, for example, in attitudes toward slavery. But in terms of the *fraction* of GDP that citizens in different states wanted the federal government to consume
or redistribute, there was probably much more agreement across member states then than there is in the United States today. Then, beyond redistributing
from taxpayers to government creditors, the federal government's redistributional activities were minimal. Some proponents of a fiscal
union in Europe today may want more redistribution and some opponents may want less.

There are lessons for the United States now. The government budget constraint and a pricing equation for government debt always prevail.
The message of the unpleasant arithmetic of {cite:t}`SargentWallace1981` is that with a responsible fiscal policy—one that sustains present value government budget balance with zero revenues from the inflation
tax—it is easy for a monetary authority to sustain low inflation; but that with a profligate fiscal policy, it is impossible for a monetary authority to sustain low inflation because the intertemporal government budget then implies that the monetary authority must sooner or later impose a sufficiently large inflation tax to finance the budget. In this sense, monetary and fiscal policies cannot be independent. They must be coordinated.
There are simple and transparent devices for coordinating fiscal and monetary policies.[^80]$\!^,$[^81]
Other more obscure ways are also possible, like one that seems to prevail in the United States today.

## Appendix: Outcomes in Graphs
Figures {numref}`fig-revenue`, {numref}`fig-expend`, {numref}`fig-per_cap_revenue`, {numref}`fig-per_cap_expend`, {numref}`fig-def_to_gdp`,
{numref}`fig-debt_gdp`, {numref}`fig-inflate`, {numref}`fig-composition`, {numref}`fig-percapreal`, and {numref}`fig-percapnominal`
show some of the fiscal outcomes of the policies that Washington and Hamilton designed.

Figures {numref}`fig-revenue` and {numref}`fig-per_cap_revenue` show federal revenues by source from 1790 to 1820, both relative to GDP and per capita, respectively.
These figures confirm that customs duties were the dominant source of federal revenues. Notice how much those revenues suffered when, during Madison and Jefferson's embargo in 1808 and 1809,
the United States did eventually use trade policy to retaliate against the British. Today, Hamilton is sometimes characterized as someone who advocated a big state, but that has to be put in the context of the 1790s when,
as figure {numref}`fig-revenue` shows, a “big state” advocate wanted to raise about 2 percent of GDP in federal revenues and to use much of those revenues to service federal debt.
Hamilton and Washington's policy of forbearance toward the British during the 1790s was designed to protect federal revenues
and to avoid the outcomes that Madison and Jefferson's policy eventually temporarily brought about. Figures {numref}`fig-expend` and {numref}`fig-per_cap_expend` show the composition of federal expenditures, both
relative to GDP and per capita, respectively. Evidently, throughout the period, a large fraction of expenditures went to servicing the federal debt.

Figure {numref}`fig-def_to_gdp` shows the ratio of the net of interest federal deficit to GDP, while figure
{numref}`fig-debt_gdp` shows the debt to GDP ratio, where debt is being valued at par. Figure {numref}`fig-inflate` shows the growth rate of GDP and the inflation rate. Both of these
figures should be viewed as subject to substantial measurement errors. Figure {numref}`fig-composition` shows the composition of the federal debt. The figure shows how the domestic unfunded debt was
converted into instruments described in the Act of August 4, 1790 and how rapidly the Treasury managed to carry out that successful debt restructuring. Notice the debt that was
issued to help purchase the Louisiana Territory in 1803.

Figures {numref}`fig-percapreal` and {numref}`fig-percapnominal` show per capita real GDP and per capita nominal GDP, again both probably subject to substantial measurement errors. Evidently,
the debt to GDP ratio shrank over the period mainly through growth in GDP.

### Data Sources

The data in these graphs come from the following sources.
Figure {numref}`fig-revenue`:
Revenue: Annual Report of the Secretary of the Treasury on the State of the Finances for the Year 1870 (Government Printing Office, Washington, 1870), Table K.
Statement of the receipts of the United States from March 4, 1789 to June 30 1870, by calendar years to 1843, and by fiscal years (ending June 30) from that time,
pages XXVI-XXVIX.
Nominal GDP: Louis Johnston and Samuel H. Williamson, “What Was the U.S. GDP Then?” *Measuring Worth* 2010. URL: $<$http://www.measuringworth.org/usgdp/$>$.
Figure {numref}`fig-expend`:
Expenditures: Annual Report of the Secretary of the Treasury on the State of the Finances for the Year 1870 (Government Printing Office, Washington, 1870), Table L.
Statement of the expenditures of the United States from March 4, 1789 to June 30 1870, by calendar years to 1843, and by fiscal years (ending June 30) from that time,
pages XXX-XXXI.
Nominal GDP: same as figure {numref}`fig-revenue`.
Figures {numref}`fig-per_cap_revenue` and
{numref}`fig-per_cap_expend`:
Same revenue and expenditure data as in Figures {numref}`fig-revenue`
and {numref}`fig-expend`. Population: HSUS Table Aa7 (the numbers include slaves). Also from Measuring Worth.
Figure {numref}`fig-def_to_gdp`:
Hall and Sargent calculated the primary deficit using the revenue and expenditure data cited above. Nominal GDP same as in Figures {numref}`fig-revenue`
and {numref}`fig-expend`. 1 and 2.
Figure {numref}`fig-debt_gdp`:
Debt: Annual Report of the Secretary of the Treasury on the State of the Finances for the Year 1870 (Government Printing Office, Washington, 1870), Table H.
Statement of the outstanding principal of the public debt of the United States on the 1st of January of each year, from 1790 to 1842, inclusive;
page XXV.
Figure {numref}`fig-inflate`: GDP deflator and real GDP growth from *Measuring Worth*.
Figure {numref}`fig-composition`:
Reports of the Secretary of the Treasury of the United States: Report on the Finances, December 1815, Table C.
Statement of the Public Debt on the 1st day of January, in each of the years, from 1791 to 1815 inclusive;
pages 47–50.
{
$<$http://fraser.stlouisfed.org/docs/publications/treasar/ar_treasury _1815.pdf$>$.}
Figures {numref}`fig-percapreal`
and {numref}`fig-percapnominal`:
*Measuring Worth*.

```{figure} ../figures/10-01_Sargent_fig.png
:name: fig-revenue
:width: 90%

Composition of federal revenues by source
```

```{figure} ../figures/10-02_Sargent_fig.png
:name: fig-expend
:width: 90%

Composition of federal expenditures by type
```

```{figure} ../figures/10-03_Sargent_fig.png
:name: fig-per_cap_revenue
:width: 90%

Per capita composition of federal revenues by source
```

```{figure} ../figures/10-04_Sargent_fig.png
:name: fig-per_cap_expend
:width: 90%

Per capita composition of federal expenditures by type
```

```{figure} ../figures/10-05_Sargent_fig.png
:name: fig-def_to_gdp
:width: 90%

Primary deficit-to-GDP ratio
```

```{figure} ../figures/10-06_Sargent_fig.png
:name: fig-debt_gdp
:width: 90%

Par value debt-to-GDP ratio
```

```{figure} ../figures/10-07_Sargent_fig.png
:name: fig-inflate
:width: 90%

Annual inflation and real GDP growth
```

```{figure} ../figures/10-08_Sargent_fig.png
:name: fig-composition
:width: 90%

Composition of the debt outstanding by type of obligation
```

```{figure} ../figures/10-09_Sargent_fig.png
:name: fig-percapreal
:width: 90%

Per capita real GDP (2005 dollars)
```

```{figure} ../figures/10-10_Sargent_fig.png
:name: fig-percapnominal
:width: 90%

Per capita nominal GDP
```

[^1]: See {cite:t}`Muth1960,Muth1961`, {cite:t}`Lucas_1972,Lucas_1976_Critique`, {cite:t}`Lucas/Stokey:1983`, {cite:t}`Lucas_Prescott_1971,Lucas_Prescott_1974`, {cite:t}`Kydland_Prescott`, {cite:t}`HS1980`, {cite:t}`HansenGMM`, {cite:t}`Sims1972,Sims:1980`, {cite:t}`Fisher_Irving`, chs. XI, XII, {cite:t}`FriedmanSchwartz`, and {cite:t}`Velde2009`. {cite:t}`Fisher_Irving`, chs. XI, XII, entitled “Statistical Verification,” set out a road map for {cite:t}`FriedmanSchwartz`. {cite:t}`Velde_Weber` beautifully formalize and extend an enlightening model of bimetallism created by {cite:t}`Fisher_Irving`. The issues described in this chapter have been with us for a very long time. See {cite:t}`Conklin:1998` for a description and analysis of sovereign debt issues faced by Spain under Phillip II.

[^2]: For an exquisite example of how theory imitates life, see {cite:t}`Velde2009` for an account of an *actual* pure change-of-units monetary experiment that is a key ingredient of the mental experiment analyzed by {cite:t}`Lucas_1972`.

[^3]: The term “framers” rather than “founders” or “founding fathers” is more descriptive of how they thought of themselves, namely, as creators of an institutional framework within which their successors would act. See {cite:t}`Rakove_meaning`.

[^4]: Also see {cite:t}`Sargent_1971,Sargent_hyper_1977,Sargent_termstructure_1979`.

[^5]: {cite:t}`Muth1960,Muth1961` began this approach. Situations in which those people who most influence prices forecast optimally can themselves be the outcomes either of long experiences from individuals' statistical learning processes (see {cite:t}`Bray_Kreps` and {cite:t}`Marcet_Sargent_1989`) or else a competitive process that somehow encourages the survival of the fittest ({cite:t}`BlumeEasley2006`). See {cite:t}`Sargent2008` for implications for macroeconomics.

[^6]: Stochastic nonsingularity means that no component of $y$ can be expressed exactly as a linear combination of past, present, and future values of other components of $y$.

[^7]: {cite:t}`HSR1991` extend this formula to handle the interesting case in which the first difference of $s_t$ is a linear combination of a stationary vector process $y_t$ like {eq}`sargVAR1`. See {cite:t}`Hansen_2011` and {cite:t}`Hansen_Sargent_Knight` for further generalizations.

[^8]: The numerator of $\kappa(z)$ is designed to contain a zero that cancels the pole at $R^{-1}$, i.e., the zero in the denominator at $R^{-1}$. This makes the Taylor series and Laurent series expansions of $\kappa(z)$ coincide.

[^9]: Related measurability requirements play a key role in {cite:t}`AMSS`.

[^10]: See {cite:t}`Sargent_1981a` for the role of those cross-equation restrictions in other contexts.

[^11]: This is the theme of the papers in the volume about rational expectations econometrics edited by {cite:t}`LucasSargent1981`, especially the introductory essay. {cite:t}`HansenGMM` and {cite:t}`Hansen_Sargent_underground` extended and refined rational expectations econometrics.

[^12]: I assume that $\phi$ and $\pi$ are constant and do not depend on the stochastic process for the net-of-interest surplus $s_t$.

[^13]: {cite:t}`Arellano_2008` used related ideas to model sovereign risk.

[^14]: Thus, there is a subtle relationship between the present value theory described in this section and causality in the sense of {cite:t}`Granger1969` and {cite:t}`Sims1972`.

[^15]: It is highly simplified relative to papers that embody standard practice today. In particular, the assumption that the interest rate is risk-free and constant is a big oversimplification. See {cite:t}`Lucas_1978`, {cite:t}`HarrisonKreps1979`, {cite:t}`HansenSingleton1983`, {cite:t}`Hansen_Richards_1987`, {cite:t}`Eaton_Gersovitz`, {cite:t}`Arellano_2008`, and {cite:t}`HansenJag1991` and references that they cite and that cite them for extensions of the basic model that relax that assumption about the interest rate.

[^16]: The adjective “superficial” is descriptive, not critical.

[^17]: {cite:t}`Kreps1997` describes common features of the equilibrium concepts used in theories of games and general equilibrium. To understand the empirical observations in the US case study presented later in this chapter might require going beyond this equilibrium concept to incorporate improvisation and adaptation in new ways that {cite:author}`Kreps1997` indicates at the end of his chapter.

[^18]: {cite:t}`Fudenberg_Levine_1993` and {cite:t}`Sargent2008` and the references there describe and apply notions of self-confirming equilibrium, a type of rational expectations equilibrium in which possibly erroneous beliefs about events that don't happen in equilibrium still have big effects on observed equilibrium outcomes.

[^19]: Goethe said it this way: “So divinely is the world organized that every one of us, in our place and time, is in balance with everything else.”

[^20]: The issue of whether equilibrium models are normative or positive was raised at a general level by {cite:t}`Sargent/Wallace:1976` and more specifically in the context of interpreting vector autoregressions by {cite:t}`Sargent_vs_Sims_1984`.

[^21]: The only time I saw Milton Friedman speechless was at a dinner party at Stanford in the mid-1980s. His close friend George Stigler trapped Friedman by asking him two questions. First, Stigler asked whether Friedman consulted for private businesses. Friedman said no, that because businessmen had more information and had already optimized, he had nothing useful to tell them. Then Stigler said, “Well that makes sense to me Milton, but then why are you always telling governments what to do?”

[^22]: Maybe it is a pattern *imposition* exercise. I did not select facts out of the blue. You can't get anywhere accepting a complete “democracy of facts,” as {cite:t}`Borges` illustrated in his story about Funes the Memorious, who refused to impose patterns because he wanted to account for everything. My exercise amounts to pattern recognition with strong preconceptions. Prejudices help because data are limited.

[^23]: The remainder of this chapter relies on empirical evidence assembled for {cite:t}`Hall_Sargent_2015`.

[^24]: {cite:t}`Cournot`, ch. 9 constructed a model of a monopolist that buys complementary inputs from $n$ monopolists. That model can be reinterpreted to explain how decision making by consensus leads to very inferior outcomes.

[^25]: Bills of credit were small denomination circulating paper notes. They were not legal tender. Before the revolution, American colonies had issued paper notes declared to be legal tender, but the British government had prohibited them from being legal tender in an act of 1764.

[^26]: See {cite:t}`Wood` for an account of differing states' debt positions and how this fed into the politics. Also see {cite:t}`Elkins_McKitrick` for a comprehensive account of the political struggles associated with creating and running US institutions during the Washington administration.

[^27]: {cite:t}`Mailath_Postlewaite` and {cite:t}`Chari_Jones_2000` explain why decentralized systems with voluntary participation cannot be relied upon to provide public goods.

[^28]: The Continental currency eventually declined to 1/40 or 1/100 of its initial value, but that inflation in the paper currency is not revealed by aggregate price indexes. {cite:t}`David_Solar` report an authoritative price index for the United States during this period. An interesting thing about their series ({cite:t}`David_Solar`, 17) is that because the unit of account was in specie, the depreciation of the paper Continental currency does not show up. It is an interesting contrast that during the US Civil War, the paper greenback displaced specie as the unit of account in most states that remained in the union. California and Oregon were exceptions. Their courts refused to enforce the federal legal tender law and they stayed on a specie standard.

[^29]: This ignites the dynamics that underlie the unpleasant arithmetic of {cite:t}`SargentWallace1981`.

[^30]: See {cite:t}`McDonald`, 170–71.

[^31]: See {cite:t}`Irwin2009` and {cite:t}`Rakove_meaning`, ch. II for the history and {cite:t}`Cournot`, ch. 9 for the theory.

[^32]: {cite:t}`Hamilton_Credit` estimated that at the beginning of 1790, the total debt at par stood at 79 million dollars, of which 25 million was owed by the states, and 12 million was owed to foreigners.

[^33]: {cite:t}`Sargent_Velde_1995` see the French Revolution through the lens of the government budget constraint.

[^34]: There is a grain of truth in a controversial interpretation of the framers' motives authored by {cite:t}`Beard`.

[^35]: A theme of {cite:t}`Wills_Madison` is that James Madison overestimated the damage that an embargo could inflict on Britain and that he underestimated the damage that it would do to American commerce and the ties that bound New England to the union.

[^36]: See {cite:t}`Sylla2009` for a comprehensive account and interesting interpretation of Hamilton's plans. Also see {cite:t}`Wright`.

[^37]: Acts of the First Congress, Second Session included the act of August 4, 1790 making provision for the debt of the United States, the act of August 5, 1790 to provide more effectually for the settlement of accounts between the United States and the individual states, and the act of August 19, 1790 making further provision for the payment of the debts of the United States.

[^38]: Remember formula {eq}`eqn-Rdefault` for the discount factor.

[^39]: Hamilton had altered creditors' views about the government's “type.” The situation of the new government in United States in 1789 reminds me of an example about sovereign default in {cite:t}`Bassetto2005`, sect. 4. Assume that a government with a dubious fiscal record leaves office and is replaced by a new government that is perfectly credible and dedicated to repay the debt. Despite the best intentions, whether or not the new government defaults is still influenced decisively by the private agents' beliefs. If they persist with beliefs that the new government will default, they will demand prohibitive interest rates, rendering even a well-meaning government eventually unable to meet its obligations at those rates. So to succeed the new government will have to implement good economic policies and also benefit from good (or lucky?) “expectations management,” whatever that means. See {cite:t}`Bassetto2006`.

[^40]: See {cite:t}`Hamilton_Credit`.

[^41]: Although the Congress defeated Madison's proposal for discrimination, a related idea returned to affect the Madison administration two decades later during the War of 1812. {cite:t}`Dewey1912`, 134 describes an act of March 24, 1814 that required the government retroactively to offer more favorable terms to previous creditors if subsequent issues garnered lower market prices.

[^42]: Proposals to discriminate among creditors often surface during negotiations to reschedule debts. For example, there are proposals for private holders of Greek government debt to take substantial voluntary haircuts while non-private creditors are to be paid in full.

[^43]: {cite:t}`McDonald`, 166–67 describes how in the early 1780s Superintendent of Finance Robert Morris tried but failed to organize the Continental Congress's domestic creditors as a nationalizing force.

[^44]: The “why pay?” question has been sharply posed by {cite:t}`Bulow/Rogoff:1989` and {cite:t}`Kletzer_Wright`.

[^45]: Sometimes they have also done whatever they could to acquire *net claims* on the private sector in order to finance future expenditures efficiently. {cite:t}`Paal` describes how the Hungarian communists deliberately reset “time $0$” after World War II and acquired claims on the public by restarting the monetary system.

[^46]: Lenin and Trotsky and their admirers in Eastern Europe did that. The leaders of the French Revolution in 1789 did not, instead struggling valiantly for years to service the pre-revolution debt until circumstances eventually forced them into a substantial default in 1797. See {cite:t}`Sargent_Velde_1995`.

[^47]: See {cite:t}`Meltzer_Richard`.

[^48]: American politics and policies toward debt management in the aftermath of the US war for independence differed strikingly, for example, from those in Germany after World War I. Domestic creditors owned most of a very large government debt that Germany had accumulated during World War I, but then the Versailles treaty imposed big further debts on the German government in the form of huge and uncertain reparations payments to some of the victors. Politics in the United States after the war for independence differed from those in Germany after World War I because the US foreign debt had come from the benevolence and trust of friends in France and Holland who had sent us resources during the war, not the vengeance of foreign powers that had defeated us, as was true in Germany. A hyperinflation produced consequences that allowed Germany to escape most of those reparations payments, albeit at the cost of tremendous collateral damage in the form of a massive redistribution away from German nominal creditors to German nominal debtors as the value of German mark depreciated from its pre–World War I value by a factor of $10^{12}$ by November 1923. {cite:t}`Sargent_Ends_1982` describes how Germany abruptly ended its hyperinflation by using a version of the simple theory {eq}`sarg1` for valuing government debt. Before November 1923, the most important component of Germany's government surplus process $s_t$ was an inflation tax. The hyperinflation was arrested by adopting policies that adjusted government expenditures and taxes, along with fortifying a central bank that would refuse to levy the inflation tax.

[^49]: That is, he wanted the option to issue debt in the fashion made explicit by Secretary of the Treasury Albert Gallatin in his 1807 report to Congress (see {cite:t}`Dewey1912`, 128), a policy later formalized in the tax-smoothing models of {cite:t}`Barro1979` and {cite:t}`AMSS`.

[^50]: See {cite:t}`KJ2010` and references cited there for modern arguments about good effects fostered by a stock of safe government debt.

[^51]: See {cite:t}`Brewer` and {cite:t}`North_Weingast` for accounts of the flexibility that the government of Britain had achieved by successfully implementing fiscal institutions that Hamilton admired. An implication of {cite:t}`Bassetto2005,Bassetto2006` is that even with good institutions and well-intentioned policy makers, sometimes there are multiple equilibria, and we need luck or skill to select among them.

[^52]: They set the seigniorage rate to zero, a decision called “free coinage.”

[^53]: Madison changed his mind, when, serving as president twenty years later, the bank's charter came up for renewal and opponents of the bank brought up Congressman Madison's 1791 arguments to use against his administration's request to renew the bank's charter. Although he changed sides, Madison was on the losing side both times, as Congress refused to renew the Bank's charter in 1811, causing the United States to finance the War of 1812 with its longstanding fiscal agent having just been abolished and scrambling to improvise alternative arrangements for acquiring short-term credit. Whether to have a national bank serving as fiscal agent of the federal government is something that statesmen like James Madison and Henry Clay changed their minds about, and so did the country. The charter of the first Bank of the United States was not renewed in 1811, and neither was the charter of the second Bank in 1836.

[^54]: Smith's real bills doctrine stresses benefits from permitting a government owned or private financial intermediary to issue circulating notes that are backed by safe evidences of private indebtedness. To Smith, “real” meant relatively risk free. Smith pointed to efficiency gains that could be gathered by allowing paper notes backed by safe private evidences of indebtedness to circulate and displace precious metals that would otherwise serve as media of exchange. See {cite:t}`Sargent_Wallace_1982` for an analysis of pros and cons of the real bills doctrine.

[^55]: Section 9 of the act of April 2, 1792 states that each dollar is “to be of the value of a Spanish milled dollar as the same is now current.”

[^56]: The US mint functioned as European mints typically did in those days. The mint stood ready to sell on demand at a fixed price, but did not purchase, gold or silver coins in exchange for gold or silver bullion, respectively. If you wanted to purchase coins from the mint, you took your bullion to the mint. The mint assayed the metal, then forged and stamped coins that they returned to you. If you wanted to melt the coins to retrieve the bullion, you could melt them yourself, or you could export or sell the coins to private parties for specie.

[^57]: To put the magnitudes in perspective, at par value, the total Continental and state debt that Hamilton rescheduled in 1790 was about 79 million dollars, which at that time was about 40% of GDP, an estimate subject to substantial uncertainty. The Louisiana Purchase was a good bargain for the United States.

[^58]: {cite:t}`Kydland_Prescott` delineated this tension. See {cite:t}`Klein_Krusell`, {cite:t}`Klein_Rios_Rull`, and {cite:t}`Debortoli_Nunes` for a small sample of an important literature in macroeconomics that uses Markov perfect equilibria to study quantitatively how outcomes under a sequential timing protocol differ from those under a timing protocol that awards a government the ability to choose once and for all. See {cite:t}`Battaglini_Coate` for a political-economic equilibrium under a sequential voting protocol.

[^59]: At the Convention on June 26, 1787, James {cite:t}`Madison_notes` said, “In framing a system which we wish to last for ages, we shd. not lose sight of the changes which ages will produce.” In 1811 Secretary of the Treasury Albert Gallatin told Congress “To meet these loans in the future we must depend on coming prosperity and the wisdom of successors; that is, favorable circumstances and rigid economy.”

[^60]: Article 1, section 10 includes the restrictions > No State shall enter into any Treaty, Alliance, or Confederation; grant Letters of Marque and Reprisal; coin > Money; emit Bills of Credit; make any Thing but gold and silver Coin a Tender in Payment of Debts; $\ldots$

[^61]: See {cite:t}`Bancroft1886` for histories of legal tender acts in colonial America and of the framers' aversion to making paper monies legal tender.

[^62]: Madison stood true on this matter. As president from 1809 to 1817, Madison presided over an administration that issued federal bills of credit to finance most expenditures for the War of 1812, but that did not make them legal tender.

[^63]: Sustaining this tradition, the confederacy did not make its paper currency a legal tender.

[^64]: {cite:author}`Bancroft1886`'s review of the evidence was prompted by what he regarded as the Supreme Court majority's flagrant disregard of the historical record in deciding the 1884 legal tender case *Juilliard v. Greenman*. The court reasoned that because Congress had the power to pay debts, it could do so by any means not expressly prohibited by the constitution; and that little attention needed to be paid the debates and votes at the constitutional convention because it was difficult to glean a consensus from them; that Congress's power to borrow money included the power to issue obligations in any appropriate form, including hand-to-hand currency; and that the authority to issue legal tender notes accompanied the right of coinage (see {cite:t}`Dewey1912`).

[^65]: Congress refused to renew the Bank's charter in 1811.

[^66]: Actually, some state-chartered banks were issuing notes before Congress chartered the first Bank of the United States.

[^67]: Free banking—in the sense of free entry—did not prevail. Most banks had to have state charters. Many of those state bank charters contained explicit provisions requiring the bank to make loans to the state or to buy bonds issued to fund canals, railroads, or turnpikes. Most of the assets that these banks purchased with notes were loans and discounts. However, banks that operated under so-called “free banking laws” were required to purchase state bonds to back their notes.

[^68]: See {cite:t}`Rolnick_Weber_1983,Rolnick_Weber_1984`. With multiple private media of exchange bearing different and fluctuating rates of return, issuers usually accepted (but did not redeem) the demand liabilities of others. An outcome was that issuers typically wanted to redeem and clear notes issued by other banks in order to augment their holdings of specie (or “lawful money”). From the 1820s to the 1850s, the Suffolk Bank of Boston successfully administered a private note clearing operation for banks from all over New England. The Suffolk Bank managed a private “currency union” in the sense that notes of New England banks circulated at par throughout the region. See {cite:t}`Weber_Suffolk`.

[^69]: Those southern interests were enthusiastic about using federal resources to pursue military adventures, like the war in Mexico opposed by Abraham Lincoln and other Whigs, through which the United States acquired territories for building additional slave states and senators.

[^70]: The Congress also passed a law granting federal land to settlers (“homesteaders”).

[^71]: One of Milton Friedman's favorites was a “law of unintended consequences.”

[^72]: Those new constitutions thereby mandated that states forego the efficiency gains of tax-smoothing delineated by {cite:t}`Barro1979` and {cite:t}`AMSS`.

[^73]: See {cite:t}`Scott_Repudiation` and {cite:t}`Ratchford`.

[^74]: See {cite:t}`Wallis_Weingast_2005`. As noted, the Eleventh Amendment to the US Constitution stated that state debts can't be enforced in federal courts. However, debts of municipal corporations and counties are enforceable in state and federal courts. {cite:t}`Adams1887` claimed that this system of arrangements for protecting investors and the balanced budget restrictions in state constitutions explain the marked shift in expenditures and debts from states to local and municipal and county governments during the 19th century. {cite:t}`Wallis2000,Wallis2001` has effectively taken up this theme.

[^75]: The story does not end here. Section 4 of the Fourteenth Amendment to the US Constitution says: > The validity of the public debt of the United States, authorized by law, including debts incurred for payment of pensions > and bounties for services in suppressing insurrection or rebellion, shall not be questioned. But neither the United States > nor any State shall assume or pay any debt or obligation incurred in aid of insurrection or rebellion against the United States, > or any claim for the loss or emancipation of any slave; but all such debts, obligations and claims shall be held illegal and void. The Fourteenth Amendment strives simultaneously to protect the reputation of federal debt and to eradicate the reputation of state debts issued by Confederate states.

[^76]: See {cite:t}`Fudenberg_Kreps_1987` for how difficult it can be to sustain distinct reputations with multiple parties. Another example of this difficulty might be that in the arrangements and decisions that it has set up to pay federal and state debts in the 1790s, the United States led by the Federalists in the 1790s had set precedents that inadvertently created expectations on the part of state creditors that it *would* backstop their profligacy.

[^77]: Related issues may return to the United States soon: Will the federal government bail out high-debt states? Should state income tax be deductible on federal tax returns, thereby administering a transfer from the frugal states to the profligate states?

[^78]: The Tories had either left or remained quiet.

[^79]: {cite:t}`Ljungqvist_Sargent` study how differences in these features of social safety nets across countries and continents can account for different outcomes for unemployment in the face of common changes in the microeconomic environment.

[^80]: Milton Friedman may have appeared abruptly to have changed his mind about how to coordinate monetary and fiscal policy, but if you look at it more deeply, he really didn't. Friedman recommended two apparently diametrically opposed ways to coordinate monetary and fiscal policy. In {cite:t}`Friedman1953`, he recommended that the monetary authority use open market operations to purchase 100% of all government debt. That put responsibility for money growth squarely on the shoulders of the fiscal authorities. To control money growth, he recommended that fiscal authorities balance the budget over the business cycle. In {cite:t}`Friedman1960`, Friedman reversed himself and instead recommended a version of the famous rule that the monetary authority commit itself to print government issued fiat money at $k$ percent per period no matter what, thereby committing itself to finance at most a small fraction of any government deficit.

[^81]: See {cite:t}`Sims_2001` for some pros and cons of “dollarization” as a coordinating device.
