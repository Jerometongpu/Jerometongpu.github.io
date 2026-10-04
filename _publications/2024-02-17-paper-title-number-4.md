---
title: "On joint marginal expected shortfall and associated contribution risk measures"
collection: publications
category: manuscripts
publication_status: published
publication_year: 2024
permalink: /publication/2024-02-17-jmes
date: 2024-07-04
online_date: 2024-07-04
venue: "Quantitative Finance"
authors:
  - "Tong Pu"
  - "Yifei Zhang"
  - "Yiying Zhang"
doi: "10.1080/14697688.2024.2366963"
excerpt: "This paper examines the additional tail losses faced by a market when both it and another market are under stress. It develops joint marginal expected shortfall and corresponding absolute and relative contribution measures, with comparison results and an application to international stock indices."
citation: "Pu, T., Zhang, Y., & Zhang, Y. (2024). &quot;On joint marginal expected shortfall and associated contribution risk measures.&quot; <i>Quantitative Finance</i>, 24(7), 889-908."
share: false
comments: false
pagination: false
---

{% include publication-metadata.html %}

## Abstract

Systemic risk is the risk that a company- or industry-level risk could trigger a huge collapse of another or even the whole institution. Various systemic risk measures have been proposed in the literature to quantify the domino and (relative) spillover effects induced by systemic risks such as the well-known CoVaR, CoES, MES and CoD risk measures, and associated contribution measures. This paper proposes another new type of systemic risk measure, called the joint marginal expected shortfall (JMES), to measure whether the MES of one entity’s risk-taking adds to another one or the overall risk conditioned on the event that the entity is already in some specified distress level. We further introduce two useful systemic risk contribution measures based on the difference function or relative ratio function of the JMES and the conventional ES, respectively. Some basic properties of these proposed measures are studied such as monotonicity, comonotonic additivity, non-identifiability and non-elicitability. For both risk measures and two different vectors of bivariate risks, we establish sufficient conditions imposed on copula structure, stress levels, and stochastic orders to compare these new measures. We further provide some numerical examples to illustrate our main findings. A real application in analyzing the risk contagion among several stock market indices is implemented to show the performances of our proposed measures compared with other commonly used measures including CoVaR, CoES, MES, and their associated contribution measures.

## Overview

The paper studies risk transmission when the recipient of a spillover is already in distress. Joint marginal expected shortfall (JMES) measures the recipient’s expected loss conditional on both its own loss and another entity’s loss exceeding separately chosen quantile thresholds. Comparing JMES with the recipient’s ordinary expected shortfall yields difference-based and ratio-based measures of the additional loss associated with joint distress.

Quantile-integral representations connect the measures to marginal loss distributions and their copula. The paper establishes conditions under which increasing stress levels or changing marginal distributions and dependence produces an ordering of JMES and its contribution measures. It also examines monotonicity and comonotonic additivity, and shows that JMES is generally neither identifiable nor elicitable on the distribution classes considered, which limits stand-alone backtesting.

An empirical study uses six major stock indices over 2007–2022 to examine spillovers from the S&P 500 to other markets. Tail models and fitted copulas allow the new measures to be compared with CoVaR, CoES and MES at several stress levels. The analysis illustrates why the choice between absolute and relative contributions matters when comparing markets whose loss distributions have different scales.
