# 1. Rational Expectations and the Reconstruction of Macroeconomics

> The government has strategies. The people have counterstrategies.
>
> — Ancient Chinese proverb

## Behavior Changes with the Rules of the Game

In order to provide quantitative advice about the effects of
alternative economic policies, economists have constructed collections
of equations known as
*econometric models*.[^1] For the most part these models consist of equations
that attempt to describe the behavior of economic agents—firms,
consumers, and governments—in terms of variables that are assumed to
be closely related to their situations. Such equations are often called
*decision rules* because they describe the decisions people make about
things like consumption rates, investment rates, and portfolios as
functions of variables that summarize the information people use to make
those decisions. For all of their mathematical sophistication,
econometric models amount to statistical devices for organizing and
detecting patterns in the past behavior of people's decision making,
patterns that can then be used as a basis for predicting their future behavior.

As devices for extrapolating future behavior from the past under a
given set of rules of the game, or government policies, these models
appear to have performed well.[^2]
They have not performed well, however, when
the rules changed. In formulating advice for policymakers, economists
have routinely used these models to predict the consequences of
historically unprecedented, hypothetical government interventions that
can only be described as changes in the rules of the game. In effect,
the models have been manipulated in a way that amounts to assuming that
people's patterns of behavior do not depend on those properties of the
environment that government interventions would change. The assumption
has been that people will act under the new rules just as they have
under the old, so that even under new rules, past behavior is still a
reliable guide to future behavior. Econometric models used in this way
have not been able to predict accurately the consequences of
historically unparalleled interventions.[^3] To take one recent example, standard Keynesian and monetarist
econometric models built in the last 1960s failed to predict the effects
on output, employment, and prices that were associated with the
unprecedented large deficits and rates of money creation of the 1970s.

Recent research has been directed at building econometric models
that take into account that people's behavior patterns will vary
systematically with changes in government policies—the rules of the
game.[^4]
Most of this research has been conducted by adherents of the
so-called hypothesis of rational expectations. They model people as
making decisions in dynamic settings in the face of well-defined
constraints. Included among these constraints are laws of motion over
time that describe such things as the taxes people must pay and the
prices of the goods they buy and sell. The hypothesis of rational
expectations is that people understand these laws of motion. The aim of
the research is to build models that can predict how people's behavior
will change when they are confronted with well-understood changes in
ways of administering taxes, government purchases, aspects of monetary
policy, and the like.

### The Investment Decision

 A simple example will illustrate both the principle that decision
rules depend on the laws of motion that agents face and the extent that
standard macroeconomics models have violated this principle. Let $k_t$
be the capital stock of an industry and $\tau_t$ be a tax rate on
capital. Let $\tau_t$ be the first element of $z_t$, a vector of
current and lagged variables, including those that the government
considers when it sets the tax rate on capital. We have $\tau_t \equiv
e^T z_t$, where $e$ is the unit vector with unity in the first
place and zeros elsewhere.[^5]
Let a firm's optimal accumulation plan require that capital acquisitions
obey[^6]

$$
\begin{split}
\ & k_t = \lambda k_{t-1} - \alpha \sum_{j=0}^\infty
\delta^j E_t \tau_{t+j} \\
 & \alpha > 0, 0 < \lambda < 1, 0 < \delta < 1 \\
 \end{split}
$$ (eq-1-1)

 where $E_t \tau_{t+j}$ is the tax rate at time $t$ that is expected
to prevail at time $t + j$.

Equation 1.1 captures the notion that the demand for capital
responds negatively to current and future tax rates. However, equation
1.1 does not become an operational investment schedule or decision rule
until we specify how agents' views about the future, $E_t \tau_{t+j}$,
are formed. Let us suppose that the actual law of motion for $z_t$ is

$$
z_{t+1} = A z_t
$$ (eq-1-2)

 where $A$ is a matrix conformable with $z_t$.[^7] If
agents understand this law of motion for $z_t$, the first element of
which is $\tau_t$, then their best forecast of $\tau_{t+j}$ is $e^T A^j
z_t$. We impose rational expectations by equating agents' expectations
$E_t \tau_{t+j}$ to this best forecast. Upon imposing rational
expectations, some algebraic manipulation implies the operational
investment schedule

$$
k_t = \lambda k_{t-1} - \alpha e^T (I - \delta A)^{-1} z_t
$$ (eq-1-3)

 In terms of the list of variables on the right-hand side, equation
(1.3) resembles versions of investment schedules that were fit in the
heyday of Keynesian macroeconomics in the 1960s. This is not unusual,
for the innovation of rational expectations reasoning is much more in
the ways equations are interpreted and manipulated to make statements
about economic policy than in the look of the equations that are fit.
Indeed, the similarity of standard and rational expectations equations
suggests what can be shown to be true generally: The rational
expectations reconstruction of macroeconomics is not mainly directed at
improving the statistical fits of Keynesian or monetarist macroeconomics
models over given historical periods and that its success or failure
cannot be judged by comparing the $R^2$'s of reconstructed
macroeconomics models with those of models constructed and interpreted
along earlier lines.

 Under the rational expectations assumption, the investment schedule
(equation (1.3)) and the laws of motion for the tax rate and the variables
that help predict it (equation (1.2)) have a common set of parameters,
namely, those of the matrix A. These parameters appear in the
investment schedule because they influence agents' expectations of how
future tax rates will affect capital. Further, notice that all of the
variables in $z_t$ appear in the investment schedule, since via equation
(1.2) all of these variables help agents forecast future tax rates.
(Compare this with the common econometric practice of using only current
and lagged values of the tax rate as proxies for expected future tax
rates.)

 The fact that equations (1.2) and (1.3) share a common set of parameters
(the A matrix) reflects the principle that firms' optimal decision rule
for accumulating capital, described as a function of current and lagged
state and information variables, will depend on the constraints (or laws
of motion) that firms face. That is, the firm's pattern of investment
behavior will respond systematically to the rules of the game for
setting the tax rate $\tau_t$. A widely understood change in the policy
for administering the tax rate can be represented as a change in the
first row of the A matrix. Any such change in the tax rate regime or
policy will thus result in a change in the investment schedule (equation
(1.3)). The dependence of the coefficients of the investment schedule on
the environmental parameters in matrix A is reasonable and readily
explicable as a reflection of the principle that agents' rules of
behavior change when they encounter changes in the environment in the
form of new laws of motion for variables that constrain them.

To illustrate this point, consider two specific tax rate policies.
First, consider the policy of a *constant* tax rate $\tau_{t+j} =
\tau_t$ for all $j \geq 0$. Then $z_t = \tau_1, A = 1$, and the
investment schedule is

$$
k_t = \lambda k_{t-1} + h_0 \tau_t
$$ (eq-1-4)

 where $h_0 = - \alpha/ (1 - \delta)$.
Now consider an investment tax credit *on-again, off-again* tax rate policy of the
form $\tau_t = - \tau_{t-1}$. In this case $z_t = \tau_1, A = -1$, and
the investment schedule becomes

$$
k_t = \lambda k_{t-1} + h_0 \tau_t
$$ (eq-1-5)

 where $h_0 = - \alpha / (1 + \delta)$.
 Here the investment schedule itself changes as the policy for
setting the tax rate changes.

 Standard econometric practice has not acknowledged that this sort of
thing happens. Returning to the more general investment example, the
usual econometric practice has been roughly as follows. First, a model
is typically specified and estimated of the form

$$
k_t = \lambda k_{t-1} + h z_t
$$ (eq-1-6)

 where $h$ is a vector of free parameters of dimension conformable
with the vector $z_t$. Second, holding the parameters $h$ fixed,
equation (1.6) is used to predict the implications of alternative paths
for the tax rate $\tau_t$. This procedure is equivalent to estimating
equation (1.4) from historical data when $\tau_t = \tau_{t-1}$ and then
using this same equation to predict the consequences for capital
accumulation of instituting an on-again, off-again tax rate policy of
the form $\tau_t = - \tau_{t-1}$. Doing this assumes that a single
investment schedule of the form of equation (1.6) can be found with a
single parameter vector $h$ that will remain fixed regardless of the
rules for administering the tax rate.[^8]

 The fact that equations (1.2) and (1.3) share a common set of parameters
implies that the search for such a regime-independent decision schedule
is misdirected and bound to fail. This theoretical presumption is
backed up by the distressing variety of instances in which estimated
econometric models have failed tests for stability of coefficients when
new data are added. This problem cannot be overcome by adopting more
sophisticated and more general lag distributions for the vector $h$, as
perhaps was hoped in the 1960s.

### Are Government Deficits Inflationary?

 A second example that well illustrates our general principles about
the interdependence of the strategic behavior of private agents and the
government concerns the inflationary effects of government deficits.
 We
can discuss this matter with the aid of a demand function for base money
of the specific form

$$
\frac{ M_t }{ p_t} = \alpha_1 - \alpha_2 E_t \frac{p_{t+1}}{p_t} \quad
\alpha_1 > \alpha_2 > 0
$$ (eq-1-7)

 where $M_t$ is the stock of base money at time $t$, $p_t$ is
the price level at time $t$ and $E_t (\cdot)$ is the value of $(\cdot)$
expected to prevail at time $t$. Equation (1.7) is a version
of the demand schedule for money that
Phillip {cite:t}`Cagan:1956` used to study hyperinflations. It depicts the demand for
base money as decreasing with the expected gross rate of inflation, $E_t
p_{t+1} / p_t$. A variety of theories imply a demand function for base
money with this property.

Equation (1.7) is a difference equation, a solution of which is

$$
p_t = \frac{ 1 }{ \alpha_1} \sum_{j=0}^{\infty} \bigl( \frac{\alpha_2}{\alpha_1}
  \bigr)^j \ E_t M_{t+j}
$$ (eq-1-8)

 which expresses the price level at $t$ as a function of the supply
of base money expected to prevail from now into the indefinite future.
We shall use equation (1.8) as our theory of the price level.

According to equation (1.8), if government deficits are to influence
the price level path, it can only be through their effect on the
expected path of base money. However, the government deficit and path
of base money are not rigidly linked in any immutable way. The reason
is that the government can, at least to a point, borrow by issuing
interest-bearing government debt, and so need not necessarily issue base
money to cover its deficit. More precisely, we can think of
representing the government's budget constraint in the form

$$
\begin{split}
 & G_t - T_t = \frac{M_t - M_{t-1} }{ p_t} + B_t - (1 +
r_{t-1}) B_{t-1} \\
& r_{t-1} \geq 0 \\
\end{split}
$$ (eq-1-9)

where
$G_t$ is real government expenditures at $t$, $T_t$ is real taxes net of transfers (except for interest payments on the government debt), $B_t$ is
the real value at $t$ of one-period government bonds issued at $t$, to
be paid off at $t+1$ and to bear interest at the net rate $r_t$.
For simplicity, equation (1.9) assumes that all government
interest-bearing debt is one period in maturity. Equation (1.9) must hold
for all periods $t$. Again for simplicity, we shall also think of
equations {eq}`eq-1-8` and {eq}`eq-1-9` as applying to an economy with no growth in
population or technical change.

Under the system formed by equations (1.8) and (1.9), the inflationary
consequences of government deficits depend sensitively on the
government's strategy for servicing the debt that it issues. We
consider first a strict Ricardian regime in which government deficits
have no effects on the rate of inflation. In this regime, the
government always finances its entire deficit or surplus by issuing or
retiring interest-bearing government debt. This regime can be
characterized by either of the following two equations, which are
equivalent in view of equation (1.9):

$$
M_t - M_{t-1} = 0
$$ (eq-1-10)

$$
B_t = E_t \sum_{j=0}^\infty R_{tj}^{-1} (T_{t+j+1} - G_{t+j+1})
$$ (eq-1-11)

where $R_{tj} = \prod_{i=0}^{j} (1 + r_{t+i})$.
Equation (1.10) states that the supply of base money is always
constant, while equation (1.11) states that the real value of government
debt equals the present value of prospective government surpluses. In
this regime a positive value of interest-bearing government debt signals
a stream of future government budgets that is in surplus in the present
value sense of equation (1.11). Increases in government debt are
temporary in a sense made precise in equation (1.11).

In the Ricardian regime, government deficits have no effects on the
price path because they are permitted to have no effects on the path of
base money. For the path of base money to be unaffected by government
deficits, it is necessary that government deficits be temporary and be
accompanied by exactly offsetting future government surpluses.

Since the Ricardian regime may seem remote as a description of
recent behavior of the US federal government, it is worthwhile to
recall that cities and states in the United States are constitutionally
forced to operate under a Ricardian rule, since they have no right to
issue base money.

 There are alternative debt-servicing strategies under which
government deficits are inflationary. To take an example at the
opposite pole from the Ricardian regime, consider the rule recommended
by Milton {cite:t}`Friedman:1948` under which

$$
B_t = 0 \ \text{for all } \ t
$$ (eq-1-12)

$$
G_t - T_t = \frac{M_t - M_{t-1} }{ P_t}
$$ (eq-1-13)

 According to this rule, deficits are always to be financed entirely
by issuing additional base money, with interest-bearing government debt
never being issued. In this regime, the time path of government
deficits affects the time path of the price level in a rigid and
immediate way that is described by equations (1.8) and (1.13). Under this
regime it is possible for the government budget to be persistently in
deficit, within limits imposed by equations (1.13) and (1.7). Deficits need
not be temporary.

{cite:t}`Bryant/Wallace:1980` and {cite:t}`SargentWallace1981` have described
debt-servicing regimes that are intermediate between Ricardo's and
Friedman's. In all versions of these regimes, interest-bearing
government debt is issued, but is eventually repaid partly by issuing
additional base money. In the regime studied by Sargent and Wallace,
the deficit path $G_t - T_t$ is set in such a way, and the demand
schedule for interest-bearing government debt is such that eventually
the inflation tax must be resorted to, with increases in base money
eventually having to be used to finance the budget.

In all regimes of the Bryant-Wallace variety, increases in
interest-bearing government debt are typically inflationary, at least
eventually because they signal prospective increases in base money.
Sooner or later these eventual increases in base money will affect the
price level, how soon depending on the coefficients $\alpha_1$ and
$\alpha_2$ in equations (1.7) and (1.8).

This discussion indicates that the observed correlation between the
government deficits and the price level depends on the debt-repayment
regime in place when the observations were made. It would be a mistake
to estimate the relationship between the deficit and the price path from
time-series observations drawn from a period under which a Ricardian
regime was in place, and to assert that this same relationship will hold
between the deficit and inflation under a regime like the one described
by Bryant and Wallace. It would be a mistake because private agents'
interpretations of observed deficits, and consequently the impact of
observed deficits on the price level, depend on the debt-servicing
regime they imagine to be in place. This can thus be viewed as another
example of our principle that private agents' rules of behavior depend
on their perceptions of the rules of the game they are playing.

## General Implications of the Examples

 These two examples illustrate the general presumption that the
systematic behavior of private agents and the random behavior of market
outcomes both will change whenever agents' constraints change, as when
government policy or other parts of the environment change. To make
reliable statements about policy interventions, we need dynamic models
and econometric procedures that are consistent with this general
presumption. Foremost, we need a new and stricter definition of the
class of parameters that can be regarded as *structural*. The body
of doctrine associated with the simultaneous equations model in
econometrics properly directs the attention of the researcher beyond
reduced-form parameters to the parameters of structural equations that
are meant to describe those aspects of people's behavior that remain
constant across a range of hypothetical environments. Although such
structural parameters are needed to analyze an interesting class of
policy interventions, most often included among them have been
parameters of equations describing the rules of choice for private
agents. Consumption functions, investment schedules, and demand functions for assets are all examples of such rules of choice. In dynamic
settings, regarding the parameters of these rules of choice as
structural or invariant under policy interventions violates the
principle that optimal decision rules depend on the environment in which
agents believe they are operating.

 If parameters of decision rules cannot be regarded as structural or
invariant under policy interventions, deeper objects that can must be
sought. The best that can be hoped for is that parameters
characterizing private agents' preferences and technologies will not
change when changes in economic policy change the environment. If
dynamic econometric models were formulated explicitly in terms of the
parameters of preferences, technologies, and constraints, in principle
they could be used to predict the effects on observed behavior of
changes in policy rules. In terms of our investment example with
equations (1.2) and (1.3), the idea would be to estimate the free parameters
of the model ($\lambda, \alpha, \delta, A$). With these estimates,
economists could predict how the investment schedule would change if
different $A$'s occurred.[^9]

## New Econometric Methods

{*Private Agents' Strategies Reflect Government's\\
Choice of Rules of the Game*}

 A major research effort is currently under way by economists to
develop theoretical and econometric methods capable of isolating
parameters that are structural in the above sense, that is, they are
invariant under government interventions in the form
of changes in the rules of the game. This is a very ambitious
undertaking, one that is in many ways more difficult and ambitious than
was the impressive effort of the Cowles Commission in the late 1940s
that created the econometric methods that made Keynesian econometric
models possible. For what is required is a theoretical and statistical
framework that permits the economist to estimate how private agents'
decision rules or strategies depend on the decision rules or strategies
used by the government. Any successful version of this research effort
will embody the principle that the parameters of private agents'
decision rules are not among the free parameters of the model, but are
themselves functions of (among other things) parameters describing the
rules used by the government. Achieving success in this endeavor
requires that many new methods and results be achieved in technical
aspects of econometrics and dynamic economic theory.

{
Lucas and Sargent have formalized the ideas behind this research
effort in the following way. They let $h$ denote a collection of
decision rules of private agents. Each element of $h$ is itself a
function that maps some private agent's information about his state at a
particular point in time into his decision at that point in time.
Consumption, investment, and demand functions for money are all examples
of elements of $h$.
Lucas and Sargent let $f$ denote a collection of
elements that forms the “environment” facing private agents. Some
elements of $f$ represent rules of the game or decision rules selected
by the government, which map the government's information at some date
into its decisions at that date. For example, included among $f$ might
be decision rules for fiscal and monetary policy variables. The
fundamental principle that we are concerned with can be summarized as
stating that the elements of $h$ are partly functions of $f$. Lucas and
Sargent represent this mapping formally by

$$
h = T\,(f)
$$ (eq-1-14)

}

 The mapping $T$ represents “cross-equation restrictions,” since
each element of $h$ and of $f$ is itself a decision rule or equation
determining the choice of some variable under an agent's control.

 The new econometric methods have been aimed principally at utilizing
time series of observations on an economy that was operating for some
period under a *single* set of government rules or
strategies.[^10] The idea
is to impose sufficient structure on the observations (i.e., sufficient
structure on the mapping $T$ in equation (1.14)) that by observing the
decisions $h$ of private agents and $f$ for the government, we can
isolate the free parameters of agents' preferences and constraints that
determine $T$ and that will enable us to predict how private agents'
decision rules $h$ would change if the government were to adopt some new
and perhaps historically unprecedented rules $f$. The theoretical
models that enable one to hope to carry off this task are characterized
by “cross-equation restrictions,” across equations for the decision
rules of private agents and the decision rules of the government. These
restrictions summarize the dependence of private agents' strategies on
the government's strategies. To understand the economic process, in the
sense of being able to predict the consequences of changes in the rules
of the game set by the government, is to understand these restrictions.
The hope is that by utilizing these restrictions, observations on an
economy operating under a single set of rules can be interpreted and
used to make predictions about how the economy would behave under brand
new rules. Possessing the ability to do this is a *sine qua non* for
scientific and quantitative evaluation of alternative government rules.

 Impressive technical progress is being made in this research
endeavor, and there are grounds for being reasonably optimistic that
economists will eventually be able to deliver econometric methods that
are useful for predicting the effects of changes in government policy
rules. However, it is wise to keep in mind what an ambitious task this
is. It requires several leaps of faith in economic theory to hope that
this line of research will realize all of its aims, although the success
of this research line will eventually have to be judged not in absolute
terms but vis-à-vis alternative lines of research designed to
achieve the same objectives.

 Though they are being developed rapidly, the new methods described
above are still in their infancy, and as yet capable of handling only
relatively small and simple dynamic systems. We now have several
interesting empirical applications of these methods, which demonstrate
their feasibility. But we are still some way from a model suitable for
analyzing many interesting questions of macroeconomic policy. This is
one reason that it is useful to pursue alternative styles of analysis
that try to reflect the basic principle that private agents' behavior
depends on the rules of the game set by the government. This brings us
to economic history.

## Historical and Cross-Country Analysis

 History provides a number of examples of economies that have
apparently operated for more or less extended periods of time under
alternative rules of the game or government strategies for selecting
fiscal, monetary, and regulatory actions. By studying records of these
economies, one can hope to find direct evidence of the dependence of
private agents' decision rules $h$ on those aspects of the environment
$f$ selected by the policy authorities. These historical records amount
to distinct pairs of observations $h_1, f_1; h_2, f_2; \cdots; h_n, f_n$
that can be viewed as observations at different points of the mapping
$T$ given by equation (1.14). In a concrete sense such a collection of
cross-regime observations permits direct observations on at least parts
of the $T$ mapping.

 These are the evident advantages of the historical or cross-country
analysis. There are also evident disadvantages. The observations on
different $h_i, f_i$ pairs usually come in the form of observations from
distant times and/or places. For this reason, the data are often so
fragmentary and questionable in quality that they are incapable of
supporting the kind of formal time-series econometric analysis described
above. Less formal methods of analysis must be used for such data. To
the extent that these less formal methods require more judgment,
discretion, and cleverness from the analyst, they are in a sense less
reproducible and automatic than are the formal methods. The weaving of
plausible heuristic stories this style of analysis involves is one of
the things that the formal time-series methods developed by rational
expectations analysts and their econometric predecessors sought to
avoid. Furthermore, it is often an arguable matter to identify
alternative countries or historical periods as operating under distinct
government policy regimes or rules of the game $f$.

Despite these genuine disadvantages of the historical and
cross-country method of study, it is my belief that such studies are
well worth the effort. The hope of getting some direct peeks at
distinct observations, however fragmentary and noisy, on the $h = T (f)$
mapping easily justifies appreciable efforts in this direction. It is
this hope that motivated the three historical chapters that comprise the
heart of this book. Besides, the practical success of the rational
expectations approach to macroeconomics perhaps ultimately depends on
whether it can become a routine device that can be used to think about
macroeconomic problems informally and on the backs of envelopes. These
chapters represent attempts to put the theory into practice in such an
informal context.

## Implications for Policymakers

 These ideas have implications not only for theoretical and
econometric practices but also for the ways in which policymakers and
their advisers think about the choices confronting them. In particular,
the rational expectations approach directs attention away from
particular isolated actions and toward choices among feasible rules of
the game, or repeated strategies for choosing policy variables. While
Keynesian and monetarists macroeconomic models have been used to try to
analyze what the effects of isolated actions would be, it is now clear
that the answers they have given have necessarily been bad, if only
because such questions are ill-posed.

 In terms of our investment example, by selecting different values
for the first row of $A$, we can analyze the effects on current and
subsequent investment of switching from one well-understood policy for
setting the tax rate to another—that is, we can analyze the effects of
different *strategies* for setting the tax rate. However, we cannot
analyze the effects on current and subsequent investment of alternative
*actions* consisting of different possible settings for the tax rate
$\tau_t$ at a particular point in time $t=t$. For in order to make
predictions, we must specify agents' views about the law of motion $A$,
and this is not done when we simply consider actions consisting of
alternative settings for $\tau_t$ at one isolated point in time. This
idea is so widely accepted as to be uncontroversial among decision
theorists (and football fans); but even today practicing macroeconomists
often ignore it.

 To take a concrete example, in the United States there was recently
interest in analyzing what would happen to the rate of domestic
extraction of oil and gas if the tax on profits of oil producers
increased a lot on a particular date. Would supply go up or down if the
tax were raised to $X$ percent on July 1? The only scientifically
respectable answer to this question is “I don't know.” Such a rise in
the oil-profits tax rate could be interpreted as reflecting one of a
variety of different tax strategies ($A$ matrices), each with different
implications for current and prospective extraction of oil.

 For example, suppose that oil companies had reason to believe that
the increase in the tax is temporary and will be repealed after the
election. In that case, they would respond by decreasing their rate of
supply now and increasing it later, thus reallocating their sales to
periods in which their shareholders get a larger share of profits and
the government a smaller share. Yet suppose that oil companies believed
that the increase in the tax rate on July 1 is only the beginning and
that further increases will follow. In that case the response to the
tax rate increase would be the reverse: to increase supply now and
decrease it later in order to benefit companies' shareholders. This
example illustrates that people's views about the government's strategy
for setting the tax rate are decisive in determining their responses to
any given actions and that the effects of actions cannot be reliably
evaluated in isolation from the policy rule or strategy of which they
are an element.

 Another version of this example can easily be
constructed for our deficit example around the question “Are large
current government deficits accompanied by tight monetary policy actions
inflationary?” This question is also ill-posed because it fails to
specify the debt repayment strategy to be used by the government. The
way in which current deficits are correlated with inflation depends
sensitively on what debt repayment regimes is in place.

 What policymakers (and econometricians) should recognize, then, is
that societies face a meaningful set of choices about alternative
economic policy regimes. For example, the proper question is not about
the size of tax cut to impose now in response to a recession but about
the proper strategy for repeatedly adjusting tax rates in response to
the state of the economy, year in and year out. Strategic questions of
this nature abound in fiscal, monetary, regulatory, and labor market
matters. Private agents face the problem of determining the government
regime under which they are operating, and they often devote
considerable resources to doing so. Whether governments realize it or
not, they do make decisions about these regimes. They would be wise to
face these decisions deliberately rather than ignore them and pretend to
be able to make good decisions by taking one seemingly unrelated action
after another.

[^1]: {cite:t}`Lucas/Sargent:1979` provide a brief explanation of econometric models and their uses in macroeconomics.

[^2]: This evidence is cited by {cite:t}`Litterman:1979` and his references.

[^3]: {cite:t}`Sims:1980` and {cite:t}`Lucas_1976_Critique` describe why econometric models can perform well in extrapolating the future from the past, assuming no changes in rules of the game, while performing poorly in predicting the consequences of changes in the rules.

[^4]: For an example of such research and extensive lists of further references, see {cite:t}`HS1980` and {cite:t}`Lucas/Sargent:1981`.

[^5]: Here $T$ denotes matrix transposition.

[^6]: The investment schedule can be derived from the following dynamic model of a firm. A firm chooses sequences of capital to maximize $$ E_0 \sum_{t=0}^\infty \beta^t \bigl[ f_1 k_t - \frac{f_2}{2} k_t^2 - f_3 k_t \tau_t - \frac{d}{2} (k_t - k_{t-1})^2 \bigr] $$ where $f_1, f_2, f_3, d > 0; 0 > \beta > 1$; and $E_0$ is the mathematical expectation operator conditioned on information known at time $0$. The maximization is subject to $k_{t-1}, \tau_t$ being known at time $t$. Maximization problems of this kind are analyzed in {cite:t}`Sargent:1979`. The parameters $\lambda, \alpha$, and $\delta$ can be shown to be functions of $f_1, f_2, f_3,$ and $d$.

[^7]: The eigenvalues of $A$ are assumed to be less than $\delta^{-1}$ in absolute value.

[^8]: This is analogous to assuming that Houston's propensity to punt on fourth down does not depend on the number of downs per series determined by the NFL rules.

[^9]: As claimed in note 8, the parameters $ \lambda, \alpha, \delta$ can be shown to be functions of the parameters $f_1, f_2, f_3, d$ of the present value function being maximized in the equation.

[^10]: If sufficient data are available, these same econometric methods can be readily modified to pooling observations on $h_i, f_i$ from several regimes $i=1, \cdots, n$ in order to estimate $T$. The reader of {cite:t}`HS1980` can immediately see how samples of data drawn from different $h_i, f_i$ can be pooled using either the maximum likelihood or method of moments estimator.
