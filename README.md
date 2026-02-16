📊 Retirement Planning Monte Carlo Simulation

Risk-Adjusted Returns | Portfolio Accumulation | Retirement Sustainability


📌 Project Overview

This project builds a comprehensive retirement planning model that integrates:
	•	Risk-return theory
	•	Volatility-adjusted expected returns
	•	Monte Carlo portfolio simulations
	•	Pre-retirement wealth accumulation modeling
	•	In-retirement sustainability testing

The model evaluates whether a retirement portfolio can both reach a target value and sustain inflation-adjusted living expenses over time.


🎯 Objectives
	•	Demonstrate how volatility impacts long-term wealth accumulation
	•	Compare arithmetic vs geometric return assumptions
	•	Simulate portfolio growth using normal distributions
	•	Evaluate probability of reaching $1M+ retirement target
	•	Test whether retirement withdrawals are sustainable
	•	Model inflation-adjusted retirement expenses


🛠 What I Built


1️⃣ Risk & Return Analysis Framework

Using historical market assumptions:
	•	Mean return (e.g., 10%)
	•	Standard deviation (e.g., 20%)

I demonstrated how:
	•	Ignoring volatility overstates future wealth
	•	Geometric returns provide a more realistic long-term expectation
	•	Continuous compounding differs from discrete compounding
	•	Volatility reduces effective long-term return using:

Adjusted Return = R - \frac{\sigma^2}{2}

This quantifies how risk erodes compounding over time.


2️⃣ Monte Carlo Simulation (Pre-Retirement Phase)

Built a 30-year simulation model:
	•	Generated normally distributed annual returns using:
=NORMSINV(RAND())
	•	Converted Z-scores into simulated portfolio returns
	•	Modeled portfolio growth with annual contributions
	•	Compared:
	•	Arithmetic future value
	•	Geometric future value
	•	Monte Carlo median outcome

Demonstrated that:
	•	Median simulated wealth is lower than arithmetic projection
	•	Volatility meaningfully reduces terminal wealth
	•	Lognormal distribution governs future portfolio values


3️⃣ Retirement Accumulation Model

Inputs included:
	•	Starting salary
	•	Contribution rate (e.g., 15%)
	•	Investment return assumption
	•	Portfolio volatility
	•	Time horizon

Modeled:
	•	Lump sum growth
	•	Contribution growth
	•	Combined portfolio value
	•	Probability of reaching target retirement threshold


4️⃣ In-Retirement Sustainability Model

Tested whether portfolio supports living expenses:
	•	Inflation-adjusted expense growth
	•	Portfolio expected return during retirement
	•	20-year sustainability horizon
	•	Withdrawal logic based on 4% rule framework

Key evaluation:
	•	If expected portfolio growth ≥ inflation-adjusted expenses → sustainable
	•	If not → portfolio depletion risk


5️⃣ Distribution Analysis

Demonstrated that:
	•	Returns are normally distributed
	•	Future portfolio values are lognormally distributed
	•	Median is more realistic than mean in forecasting wealth

Created histograms and distribution visualizations to illustrate skewness and downside truncation.


📊 Key Skills Demonstrated
	•	Monte Carlo simulation modeling
	•	Risk-adjusted return calculations
	•	Volatility impact analysis
	•	Retirement planning analytics
	•	Portfolio sustainability modeling
	•	Inflation-adjusted forecasting
	•	Continuous vs discrete compounding
	•	Lognormal distribution interpretation
	•	Financial planning strategy analysis


📈 What This Project Demonstrates

This project shows the ability to:
	•	Translate financial theory into executable models
	•	Quantify how volatility impacts wealth accumulation
	•	Simulate thousands of future portfolio paths
	•	Evaluate probability-based retirement success
	•	Distinguish between arithmetic and geometric return assumptions
	•	Model both accumulation and withdrawal phases


🧠 Tools Used
	•	Microsoft Excel
	•	Monte Carlo simulation logic
	•	Normal & lognormal distributions
	•	Risk-return modeling
	•	Geometric return adjustments
	•	Financial mathematics (continuous compounding)
