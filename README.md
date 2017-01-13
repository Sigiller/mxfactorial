# mxfactorial
[![mxfactorial](https://cloud.githubusercontent.com/assets/12200465/12700510/1a48b412-c79b-11e5-901f-4f26965dd017.png)](http://www.systemaccounting.org/math_identity)

[![Coverage Status](https://coveralls.io/repos/github/systemaccounting/mxfactorial/badge.svg?branch=master)](https://coveralls.io/github/systemaccounting/mxfactorial?branch=master) [![Build Status](https://travis-ci.org/systemaccounting/mxfactorial.svg?branch=master)](https://travis-ci.org/systemaccounting/mxfactorial) [![Production Environment](https://img.shields.io/badge/PROD-gcloud-brightgreen.svg)](https://mxfactorial.io/) [![Join the chat at https://gitter.im/systemaccounting/mxfactorial](https://badges.gitter.im/systemaccounting/mxfactorial.svg)](https://gitter.im/systemaccounting/mxfactorial?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![PayPal button](https://img.shields.io/badge/donate-paypal-brightgreen.svg)](https://systemaccounting.nationbuilder.com/financial_endorsement)

*The idea is to have the U.S. Treasury deploy a payment platform where the transaction data serves as the source for measuring the cost of capital. Instead of the cost of credit determining the cost of capital, the reference for the system's risk-free rate in systemaccounting is the cost of equity. - [@Mxfactorial](https://twitter.com/mxfactorial)*

Public demonstration of the following use cases through a systemaccounting function:
* `SELECT SUM(transaction_amount) FROM transaction_table WHERE transaction_time='YYYY-MM-DD hh:mm:ss';` maximizes & protects for individuals a scientific standard the publicly-measured quarterly or annual '[GDP](https://en.wikipedia.org/wiki/Gross_domestic_product)' violates
* financial value is a [bivector](https://en.wikipedia.org/wiki/Bivector)-valued function of buyers & sellers [swapping](https://en.wikipedia.org/wiki/Position_(vector)#Derivatives_of_position) [ownership-coordinates](https://en.wikipedia.org/wiki/Bipolar_coordinates) of goods & services they measure to have *[dimension](https://en.wikipedia.org/wiki/Physical_quantity)* throughout [recursively](https://en.wikipedia.org/wiki/Recurrence_relation)-defined, [curl-](https://en.wikipedia.org/wiki/Curl_(mathematics))standardized time-coordinates (the [dual positive and negative](https://en.wikipedia.org/wiki/Hodge_dual#Four_dimensions) string values caused by the anticommutativity of the `"Seller" ∧ "Buyer" = - ("Buyer" ∧ "Seller")` exterior product form the [continuity point](https://en.wikipedia.org/wiki/Connected_space#Path_connectedness) a [time-dependent](https://en.wikipedia.org/wiki/Time-scale_calculus) projection depends on to propagate [zero-sum](https://en.wikipedia.org/wiki/Zero-sum_game) changes to account balances)
* establishing the conditions studied by [combinatorial game theory](https://en.wikipedia.org/wiki/Combinatorial_game_theory) through [physics & data science](http://www.systemaccounting.org/physics_of_value) ends public dependency on such resources as [credit ratings](https://en.wikipedia.org/wiki/Bond_credit_rating), [quarterly filings](https://en.wikipedia.org/wiki/Form_10-Q), the Consumer Price Index ([CPI](https://en.wikipedia.org/wiki/Consumer_price_index)), and the Federal Reserve Economic Data ([FRED](https://en.wikipedia.org/wiki/Federal_Reserve_Economic_Data)) platform
* disambiguating *delivered* value from *expected* value by enforcing a [law of conservation](https://en.wikipedia.org/wiki/Conservation_law) of value & liability (information) eliminates the possibility of [socializing](https://en.wikipedia.org/wiki/Externality#Negative) the [default risk](https://en.wikipedia.org/wiki/Liability_(financial_accounting)) of any individual, firm, or industry (difficult to avoid when an industry is [chartered](http://www.occ.gov/topics/licensing/index-licensing.html), [protected](https://en.wikipedia.org/wiki/Bailout), and [primarily depended upon](http://www.opensecrets.org/industries./) by a government requiring [election assistance](https://en.wikipedia.org/wiki/Collusion))
* producing a [scientific measure](http://www.systemaccounting.org/how_does_systemaccounting_produce_a_scientific_measure_of_the_cost_of_capital) of the equilibrium price of capital removes the ability of a [central authority](https://en.wikipedia.org/wiki/Central_bank) to [manipulate](https://en.wikipedia.org/wiki/Federal_funds_rate) the price of credit
* enabling transaction automation through user-generated, open-source [Transaction Rule Scripts](https://github.com/systemaccounting/mxfactorial/issues/3) written in plain JavaScript **(input)**
* maintaining publicly-accessible static and streaming endpoints servicing third-party visualization and [optimization](https://en.wikipedia.org/wiki/Combinatorial_optimization) **(output)**

This public project is intended to exploit the software engineering community's familiarity with data science to rapidly develop their capacity to [describe](https://en.wikipedia.org/wiki/Conformal_geometric_algebra) an economy from the [viewpoint](https://en.wikipedia.org/wiki/Versor) of a physicist. Software engineers may be expediently converted into PhD-level economic experts because they come equipped with the technology to efficiently approach the subject in a purely scientific manner. For example, one may avoid all the trivial complexities that currently plague the fields of economics & finance by delivering the following requirement in [Feature #2](https://github.com/systemaccounting/mxfactorial/issues/2) of the project, "A **[4D null vector](https://en.wikipedia.org/wiki/Minkowski_space#Causal_structure)** of *risk-free* value is measured when the *db_time* **AND** *cr_time* properties of a **[transaction](https://en.wikipedia.org/wiki/Action_(physics))** record receive datetime values from [a pair](https://en.wikipedia.org/wiki/Spacetime_algebra#Spacetime_split) of debiting & crediting users." Implementing a use case modeling the relationship between creditors & debitors individually negotiating a [law of conservation of value](https://en.wikipedia.org/wiki/Continuity_equation) reveals the necessity of a sequence IF stored value is to function as a [physical quantity](https://en.wikipedia.org/wiki/Potential_energy), "A purchase in the future (consumption) is a [reflection](https://en.wikipedia.org/wiki/Improper_rotation) of a sale in the past (production)." Identifying for engineers how physical value (x,y,z) is [transmitted & received](https://en.wikipedia.org/wiki/Bivector#Spacetime_rotations) with respect to [time](https://en.wikipedia.org/wiki/Angular_frequency) (t) between [sellers (1/2,π,π,π) & buyers (1/2,π,π,π)](https://en.wikipedia.org/wiki/Plane_of_rotation#Plane_of_rotation) enables them to teach the public how physical value is therefore [***added*** with respect to time](https://en.wikipedia.org/wiki/Divergence_theorem), a.k.a. the *time-value of money*, the *cost of money*, the *cost* or *price of capital*, etc. Adding to the project's **[list of features](https://github.com/systemaccounting/mxfactorial/issues?q=is%3Aissue+is%3Apublic+sort%3Acreated-asc)** is designed to foster enough interaction between engineers and the data model that a movement to eliminate nothing but [public ignorance](https://en.wikipedia.org/wiki/Pareto_efficiency) becomes generally accepted as possible *only* when it's precipitated by activism pursued—not in the streets where slogans, bottles, and rocks are blindly hurled at others who are equally frustrated with their economy, but on knowledge's frontier where math, science, and technology are used as tools to empower mankind's *movement in the cloud*.

# How to Contribute
* Supporters preferring to contribute financial resources may do so from the [Financial Support](https://systemaccounting.nationbuilder.com/financial_endorsement) page. To contribute engineering resources, download & install [Node.js](https://nodejs.org/en/download/).
* If you're not familiar with Node.js, or don't know how to code, begin the [freecodecamp.com](https://www.freecodecamp.com/) curriculum.
* Learn to build & deploy a web application on Firebase by [completing a sample](https://firebase.google.com/docs/samples/).
* Learn to deploy a Node.js web application by completing the Google App Engine ['Hello World!' tutorial](https://cloud.google.com/nodejs/getting-started/hello-world).
* Now that your development & production environments are set up, you may follow this project's [Code Delivery Workflow](https://docs.google.com/document/d/1UGklz7LwzES3t6i5IZrnt-ZwLeEFaeWhqaocFE3C9QE/edit?usp=sharing).
 
Details as of 11/15/2016:
- Production: [mxfactorial.io](https://mxfactorial.io/)
- [Data Model](https://docs.google.com/document/d/1US0gamuV3ExzUWAnNHxdcfmUxB0tPbtxUBVRBmZKywA/edit?usp=sharing)
- [Wireframes](https://drive.google.com/folderview?id=0B9xlXsaN9dVQR1EyY3dQbnZ0aG8&usp=sharing)
- [Public drive](https://drive.google.com/drive/folders/0B9xlXsaN9dVQWkJERUxNRVZQVWc)
- Node.js v4.4.3
- npm v3.5.1
- web client & database on Firebase
- API on App Engine Flex

Roadmap:
* Set up managed application & persistence layer
* Produce requirements & code for:
  * data model
  * endpoints
  * mobile web client for transactions (write) 
  * mobile-enabled web client for visualizing economic activity (read) through the [Data Layer](https://developers.google.com/maps/documentation/javascript/datalayer) feature of the Google Maps Javascript API

**Note**: Both transaction and visualization clients will be strictly served by publicly-accessible endpoints to demonstrate for the U.S. Treasury that with enough security, anyone may build an app that submits transaction data to the public ledger, thereby eliminating "banks" from the [value transmission](http://www.systemaccounting.org/what_is_money) equation.
