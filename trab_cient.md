---
title: 'Trabajos Científicos'
---

<!--
- {cite}`amster2026delayinduceddynamicsnonlinearcrime`: ecuaciones diferenciales con retardo, modelización dinámica poblacional criminal.
-->
:::{dropdown} {cite}`amster2026delayinduceddynamicsnonlinearcrime`: ecuaciones diferenciales con retardo, modelización dinámica poblacional criminal.
A nonlinear time-delay model is proposed to describe the interaction dynamics between criminal and non-criminal populations, combining social influence mechanisms, saturation effects represented by a Holling type II functional response, and time-dependent law-enforcement actions. The delay accounts for the latency between exposure to criminal behavior and behavioral response, introducing memory effects that naturally lead to a delay differential equations framework. Fundamental analytical properties, including positivity, global existence, and invariance of the feasible region, are established to ensure the mathematical consistency of the population interpretation. In the autonomous setting, explicit threshold conditions governing the stability of the criminal-free equilibrium and the emergence of coexistence states are derived, while the delay is shown to induce stability switches and oscillatory regimes through characteristic root crossings. In the non-autonomous case, topological degree arguments guaranty the existence of strictly positive periodic solutions, indicating that long-term dynamics depend primarily on the averaged law enforcement intensity measures rather than on short-term fluctuations. These results identify time delay as a key structural mechanism underlying recurrent patterns and complex temporal behavior in crime dynamics.
:::

:::{dropdown} {cite}`álvarez2026crimesiroptimalcontrolproblem`: control óptimo, dinámica poblacional criminal.
This paper proposes a mathematical framework based on optimal control theory to analyze youth-related criminal dynamics in urban settings. Crime is modeled through an SIR-type compartmental system describing transitions between susceptible, criminally involved, and rehabilitated populations. Public interventions are formalized via the optimal control problem
\begin{equation*}
\min_{u_1,u_2,u_3}\int_{0}^{t_{\text{F}}} \left( I(t) -
R(t) + \frac{\mathscr{C}_1}{2} u_1^2(t) + \frac{\mathscr{C}_2}{2} u_2^2(t) + \frac{\mathscr{C}_3}{2} u_3^2(t) \right) \, dt,
\end{equation*}
subject to the SIR dynamics
\begin{equation*}
\left\{
\begin{aligned}
    \dot{S} &= \Lambda - (1-u_1)h(S)I - \mu S + ((1+u_3)\gamma_2)I + \rho \Omega R, \\
    \dot{I} &= (1-u_1)h(S)I - (\mu + \delta_1)I - ((1+u_2)\gamma_1)I - ((1+u_3)\gamma_2)I + (1-\Omega)\rho R,\\
    \dot{R} &= ((1+u_2)\gamma_1)I - (\mu + \delta_2 + \rho)R.
\end{aligned}
\right.
\end{equation*}
where the control variables represent preventive, punitive, and social reintegration policies under resource constraints. Analytical results establish positivity, invariance, equilibrium exis\-tence, and local stability properties, including the characterization of crime-free and crime-endemic equilibria through a threshold parameter. As a case study, the model and optimal policies are numerically validated using data from En la Buena!, a youth-oriented government program currently implemented by the Municipality of Santiago de Cali, Colombia, illustrating the cost-effectiveness of integrated intervention strategies and how optimal policy combinations can reduce youth involvement in criminal dynamics in urban contexts marked by structural inequality.
:::
