---
title: "Readling List Summary"
author: "Yohan Min"
date: "Updated 2020-05-28"
output:
  html_document:
    df_print: paged
    keep_md: yes
    toc: true
    number_sections: true
  word_document: default
  pdf_document: default
endnote: no
header-includes:
- \usepackage{float}
- \floatplacement{figure}{H}
- \usepackage[fontsize=12pt]{scrextend}
csl: journal-of-construction-engineering-and-management.csl
always_allow_html: yes
---



The United States, like many countries across the world, is transitioning from energy markets that rely heavily on fossil fuel resources to those that increasingly rely on low-carbon, efficient, and advanced energy resources. The potential benefits of this transition are significant. This transition, however, will not be just if the burdens are disproportionately received by certain populations, if populations are excluded from the new opportunities it provides, or if decision-making processes are not accessible to all. 

**1. Diffusion**

# Graziano, M., Fiaschetti, M., and Atkinson-Palombo, C. (2019). “Peer effects in the adoption of solar energy technologies in the United States: An urban case study.” Energy Research & Social Science, 48, 75–84.

> Addressing spatial peer-effects (SPEs) and spatial spillovers regarding the built environment and jurisdictional boundaries with cross-sectional (OLS), panel (temporal), and spatial models. 

## Findings 

* SPE decays as time passed and distance increased depending on the built environment.
* The study areas are the most income and minority segregated regions as a good stepping stone for dynamics of SPE. 
* Lack of split-incentives between landload and renter in multi-family buildings (Bronin 2012). 
* Spatial gaps as disaggregators in terms of social interaction. 
* Spatiotemporal, built environment, socioeconomic variables using fixed effects including SPE by applying spatial factors within 0.5 to 4 miles in addition to addressing spatial spillovers using SAR model, a special case of the general spatial durbin model (SDM) also adding individual fixed effect and time effect. 
* To focus on multi-family by solar cooperatives, and community organizations (Noll et al. 2014) and densely populated areas, lower-income areas by share-ownership initiatives to promote diffusion.
* Centralized, non-voluntary support policies may be necessary for implementing beyond town-level. 

# Balta-Ozkan, N., Yildirim, J., and Connor, P. M. (2015). “Regional distribution of photovoltaic deployment in the UK and its determinants: A spatial econometric approach.” Energy Economics, 51, 417–429.

> Demand for electricity, population density, pollution levels, education, and housing types using spatial econometrics methods - spatial Durbin model - for PV uptake with spillover effects. 


* Higher uptake of PV is a challenge to network operator to keep enough capacity and voltage. 
* Spatial model offer insights into spatial dynamics of the diffusion of innovations (clean tech.) which helps future policies to enable transition to a low carbon economy that is just, efficient, and effective. 
* Ignoring spatial dependence leads to baised and inconsistent estimate and loss of efficiency. 
* FiT subject to decrease to match real world cost reduction. 

## Drivers 

Key drivers for PV uptakes are accumulated capital and financial savings rather than income. 

* Graziano and Gillingham (2014) spatial neighbouring effects, built environment, and policy variables. 
* Hofierka et a. (2014) home ownership and neighbourhood effects. 
* Keirstead (2007) higher income, home owners
* Muller and Rode (2013) less dense population, single family home
* Davidson et al. (2014) education 
* Suri et al. (2007) solar irradiation 
* Snape (2013) built environment (sun facing roof) in urban than rural 
* Urban and Scasny's (2012) wealthy homeowners less reduce their net energy use.

## Models 

$$
\begin{aligned}
Y_t = \rho WY+X\beta+WX\theta+u,
\end{aligned} 
$$
where $\rho$ is a spatial qutogregressive parameter, and $\theta$ is a spatial lag in the independent variables. 

MLE estimates the function then, LR examines SDM to SAR, SEM, or OLS

* Spatial Durbin model (having both SAR and SEM)
* Spatial autoregressive model (SAR)
* Spatial error model (SEM)

Moran's I for tendency toward clustering or dispersion 

## Critique

* Onwership and single family housing are strongly correlated leading to one of them becoming negative. It needs dimension reduction, factor analysis or latent analysis. 
* Diffusion has a spatiotemporal dimension that network spillovers will be enhanced in time. 

## To check

* Multicollinearity check using variance inflation factor (VIF) for dimension reduction (FA) 
* Mismatching - comparison with PV potential mapping, solar irradiation mapping
* Factors - peer effect, education, income, homeownership, housing structure, irradiation, etc. 
* Models - SAR, SEM 
* Equity issue for households (less irradiation, funding, built environment) to access tariffs (incentives).


# Dharshing, S. (2017). “Household dynamics of technology adoption: A spatial econometric analysis of residential solar photovoltaic (PV) systems in Germany.” Energy Research & Social Science, 23, 113–124.

> Economic factors, socio-demographic and attitudinal adopter characteristics, settlement structure, and spillover effects between neighboring counties using SAR and SEM. Economic incentives impact on PV adoption.  

* To increase the geographic and social diversification of PV adoption patterns. 
* Promoting solar leasing or community investment models which make PV accessible to a less affluent mass market. 
* High upfront cost is the barriers to adoption (Allen et al. 2008, Scarpa et al. 2010)

## Drivers 

* Graziano et al. (2014) owner occupied, single family, suburban and rural, preexisting PV installations
* Bollinger et al. (2012) additional installation increases likelihood of adoption, stronger peer effect 
* Schaffer et a. (2012) solar irradiation 
* Islam (2014) payback, energy cost savings
* Urbanization (Rode et al. 2012), single-family homes, owner-occupied units (Muller et al 2013)
* Scott et al. (2011) Peer effects (imitation, herd behavior, and social interaction)
    * active: solar advocacy 
    * passive: visibility in neighborhood
    
* Seel et al. (2014) Transaction cost (time spent on negotiating)

## Models

* DV: # of PV installation/ # of owner-occupied buildings
* Spatial panel models over cross-sectional models: time-variying correlated unobservables controlled. 
* Lagrange Multiplier (LM) test for spatial autocorrelation
* Hausman test for choosing between the random and the fixed effects model of spatial panel regression 
* Lambda for SAR; Pho for SEM

## Critique

* Modifiable areal unit problem (MAUP) in scale and zoning
* Spatial spillover effects (solar clusters) for grid planning and visibility of PV (social multiplication) (Dastrup et al. 2012)
* Influence of local advocacy groups to be addressed 
* Many variables used - dimension reduction necessary 

## To check 

* Multi-family homes and renter-occupied units which are common in the urban lack incentives (Gillingham et al. 2012)
* To address imbalances in PV adoption, policies to take local-specific mearues
* Less affluent households (renters) to join in the PV market - leasing busienss (Drury et al. 2012), community solar (Funkhouser 2015)
* Community ownership to increase PV adoption, local acceptance of RE (Wustenhagen et al. 2007)
* Due to PV incentives, uneven distribution leads to a redistribution of income mainly benefiting counties with faborable factors such as geographic conditions


# Heymann, F., Lopes, M., vom Scheidt, F., Silva, J. M., Duenas, P., Soares, F. J., and Miranda, V. (2019). “DER adopter analysis using spatial autocorrelation and information gain ratio under different census-data aggregation levels.” IET Renewable Power Generation.

> DER apopter analysis per technologies (PV, EV, and HVAC) and aggregating scales

* Comparison of distribution patterns per tech and aggregating scales 
* Diffusion study to policy analysis and electricity network planning 
* EV and PV follow the similar distribution patterns and similar adopters?
* Electricity network planning to consider uneven distribution for investment plan
* Difference of EV and PV adoption for energy policy design in consideration of synergies and distributional justice 
* Will help to design DER spport schemes for maximising penetration and reducing network expansion costs

# Palm, A. (2017). “Peer effects in residential solar photovoltaics adoption—A mixed methods study of Swedish users.” Energy Research & Social Science, 26, 1–10.

> Identifying local factors to PV diffusion through surveys to PV adopters and comparison with lower diffusion municipalities. Peer effects and local orgainisations promoting PV are the most important while utilties taking role by having the surplus from PV, selling turnkey PV, and disseminating information through seminars and web. 

## Drivers

* PV distribution patterns can not be explained only by economic profitability alone - insolation, electricity price, financial incentives, etc. (Karteris and Papadopoulos 2012). 
* Muller and Rode (2013) peer effects based on spatial and temporal distance between installations. 
* Rai and Robinson (2013) passive and active peer effects 
* Brudermann et al. (2013) word of mouth and informative meetings

## Findings 

* Social influence on decision making is underestimated (Nolan et al. 2008)
* Benefits of utilities selling PV over the installation firms (higher credibility, lower risk, lower transaction costs)
* Bank for financing to increase the diffusion 


# Strupeit, L., and Palm, A. (2016). “Overcoming barriers to renewable energy diffusion: business models for customer-sited solar photovoltaics in Japan, Germany and the United States.” Journal of Cleaner Production, Advancing Sustainable Solutions: An Interdisciplinary and Collaborative Research Agenda, 123, 124–136.

> Different business models (organizational configurations) created from contextual conditions or socio-political environment for diffusion

## Findings 

* PV policies mostly for financial incentives and setting targets, but diffusion is not only from incentives, but also from the removal of barriers and transaction costs. 
* Policies to focus on streamlining and facilitation of legal-administrative processes, solar loan, and implementation of certain PV model regarding policy framework, transaction costs, the electricity market, the building sector, and consumer-related factors. 
* Barriers: consumer inertia, up-front cost, long payback, information gaps, PV reliability, complex process (Shih et al. 2011)
* Business models as catalysts for the diffusion by overcoming barriers (Boons et al. 2013). 
* Product-service systems (PSS): 
    * US: use-oriented (leasing) and result-oriented (PPA), which increase the utilisation rate saving resources. Since firms cannot refinance interal costs by increasing the utilization rate of Pv unlike car-sharing, consumers will benefit more by owning PV. This model is more suitable for early market. 
    * Japan and Germany: product-oriented for mature market. 
    
    
* US: solar service firms, third-party ownership (TPO), leasing models with PPA, lower transaction cost for incentives, permitting, system installation, reducing the contacts with installers, maintenance, banks, insurers, and government agencies. 
    * Solar service firms collecting PV projects into a fund for selling to investors (Hobbs et al. 2013).
    * Ownerless consumption attractive to lower financed customers for a capital-intensive technology (Mont et al. 2006)
    * Transaction efficiency by the reduction of uncertainty, complexity, information asymmetry (Amit and Zott, 2001).

* Germany: mostly ownership with local craft firms due to Fit, low-interest loans.
    * Economic viability (Sonnberger 2014) and a guaranteed revenue rate per kWh (Bundesgesetzblatt 2000). 
    * Moving from feed-in to self-consumption model. 

* Japan: PV into perfabricated homes reducing cost of customer acquisition about 1-3% of PV compared to 9-10% in the US (Friedman et al. 2014). 
    * PV with new home is about 10% cheaper than retrofit systems (METI 2014) and more satisfaction than other Pv owners (Mukai et al. 2011). 
    * Transaction cost and interest rates are cheaper for both parties by being integrated into the home mortgage. 
    * Having anchoring effect (Mukai et al. 2011). 
    

# Mah, D. N., Wang, G., Lo, K., Leung, M. K. H., Hills, P., and Lo, A. Y. (2018). “Barriers and policy enablers for solar photovoltaics (PV) in cities: Perspectives of potential adopters in Hong Kong.” Renewable and Sustainable Energy Reviews, 92, 921–936.

> Barriers to urban PV: high upfront cost and long payback, residential - subsidies, industrial - regulatory measures, commercial - FiT. 

## Findings 

* Factors to diffusion: technical suitability (space constraints, intermittency, grid connection limitations), economic viability (payback, high costs), market factors (misplaced incentives, unpriced costs, access to finance), regulatory (permission process, vested interests against new energy options), social acceptance (lack of information, community involvement). 

* Government interventions, policies: subsidies, regulatory measures, FiT, net metering, technical support. 

# Wolske, K. S., Todd, A., Rossol, M., McCall, J., and Sigrin, B. (2018). “Accelerating demand for residential solar photovoltaics: Can simple framing strategies increase consumer interest?” Global Environmental Change, 53, 68–77.

> Strategies in behavior economics and psychology to increase the financial apeal of PV. Underlying consumer motivations and predispositions (perceived social support, consumer innovativeness) over behavior economics and psychology are the primary factors. Tailoring messages to targeted consumer is more effective than financial benefits to broad audiences. 

## Findings 

* Based on behavior economics and psychology, small strategic changes could be cost-effective.
* Loss frames and different temporal scales more finacially apealing? 
    * Prospect theory, the pain of a potential loss more powerful than the pleasure of the gain leading to risk-seeking behaviors to avoid potential losses. 

* Construal level theory (CLT), perceived psychological distance (Trope and Liberman 2010):
    * Loss framed messages, how to take action, concrete, detail-rich, present-focused, low-level construal. 
    * Gain framed messages, why to take action, abstract, low-in detail, future-oriented, high-construal. 
    
* Customer acquisition costs is a barrier to lowering PV costs. 
* Information need to come from trusted sources (Noll et al. 2014). 
* Importance of perceived soial support and peer effects by highliting pro-solar opinion leaders, hosting workshops, connecting consumers with PV adopters in the community (Noll. et al. 2014). 
* Effects of the ads were minimal compared to those of consumer characteristcs in an early adoption stage. 
* Once market is matured, the factors that influence consumerdecision making shift (Heiskanen and Matschoss 2017). 
* So if PV market is matured, it is possible that gain/ loss frame, perceived temporal distance, clarity of marketing claims may have stronger influences. 

# Curtius, H. C., Hille, S. L., Berger, C., Hahnel, U. J. J., and Wüstenhagen, R. (2018). “Shotgun or snowball approach? Accelerating the diffusion of rooftop solar photovoltaics through peer effects and social norms.” Energy Policy, 118, 596–602.

> Social influences on the decision to PV adoption, snowball effects by facilitating the creation of regional hot spots over the shotgun approach of uniform nationwide incentives. 

## Findings 

* PV adoptions from financial (the advent of grid parity) and behavioral factors (social contagion or peer effects).
* How and why peer effects to the decision to adopt? 
    * Descriptive norms: what people do, typical, normal, people confirm this norm especially under condition of high uncertainty (Cialdini 1983).  
    * Injunctive norms: what people approve, socially expected
    * the number of PV installation (IV, descriptive norm) affects PV installation (DV) through social pressure (Mediator, injunctive norm). 
    * A higher number of PV in neighborhood (IV) resulted in stronger social pressure (Mediator) as well as intentions to install PV (DV). 
* Peer effects by the strength of interpersonal ties and geographical proximity. 
* Adoption increases with the existence of previous PV (Bollinger and Gillingham 2012).
* Snowball effects taking insigths from social psychology into account over traditional shotgun approach of uniform nationwide incentives by inducing regional hot spots will work. 
* This can be done by co-investments with local authorities or PPP, solarize campaigns. 
* With financial incentives, peer effects will achieve diffusion in the targeted communities. 
* Peer effects play an important role in the early adoption stage of S-shaped diffusion curve (Rogers 1962), not sure in the matured market though. 
* Future study: potential dark side of social norms such as reactance to PV installation.

# Muchunku, C., Ulsrud, K., Palit, D., and Jonker‐Klunne, W. (2018). “Diffusion of solar PV in East Africa: What can be learned from private sector delivery models?” WIREs Energy and Environment, 7(3), e282.

> Delivery models for off-grid PV: retail, PASYG, consumer financing, mini-grid, fee-for-service. 

## Findings 

* 70% of world's population without access to electricity is good for mini-grids or stand-alone systems because of high costs, technical losses, grid extension is not suitable for remote areas. 
* Retail/ over the counter: selling products. 
* PAYG: product in addition to consumer finance and consumer pays back to the supplier via mobile money. 
* Consumer financing: partnership between a supplier and a financial institute, difference from PAYG is the difference of the role in that FI will provide consumers financing. 
* Mini-grid: viable if there are a large number of large electricity users and good for rural, centralized approach. 
* Fee-for-service: through stand-alone system, decentralized approach. 
* Capital investment on infrastructure to reach off-grid customers is financed using government budgets, levies on consumers, loans from development agencies. As not economical, utilities have little incentive to serve rural consumers. 
* Retail and PAYG are commercially viable, consumer FI is a promising commercial model, mini-grid and fee-for-service model are not commercially viable in the short term so innovative PPP could be applied to the rural. 

_____

**2. Integration**

# van der Kam, M., and van Sark, W. (2015). “Smart charging of electric vehicles with photovoltaic power and vehicle-to-grid technology in a microgrid; a case study.” Applied Energy, 152, 20–30.

> PV power, EV (use and V2G), and electricity demand with respect to PV self-consumption and peak demand reduction to prove the benefits of smart EVs with PV. 

## Findings 

* A higher PV and EV penetrations will increase power transport over the grid requiring grid investments to prevent overloads. 
* Self-consumption of PV will ensure grid stability. 
* Load shifting is an essential aspect of smart grid. 
* EV as a flexible demand source and a storage using V2G.
* EV and PV higher than 50% penetration rates will have a significant impact on the network while having the synergy (Tuffner et al. 2012). 
* Demand profile of uncontrollable load are estimated by 400 unique household profiles.
* The impact of different smart charging algorithms (reat time, RT with V2G, and LP) on energy demand regarding load profiles with PV power, uncontrollable load, and EV can be evaluated with load duration curves. 
* V2G increases battry use that impacts on battery life.
* Combination of PV and EV will reduce negative impact on the existing energy infra. 


# van der Kam, M. J., Meelen, A. A. H., van Sark, W. G. J. H. M., and Alkemade, F. (2018). “Diffusion of solar photovoltaic systems and electric vehicles among Dutch consumers: Implications for the energy transition.” Energy Research & Social Science, 46, 68–85.

> Identify the difference between PV and EV adapter groups based on socio-demographic characteristics leading to regional diffusion patterns. Then, influence of the patterns on the viability of EV-PV integration regarding energy use and regional self-consumption. Impact of diffusions on the local energy system and assessing the viability of the integration of PV and EV. Taking spatial diffusion patterns is important in energy planning. 

## Findings 

* Higher level of PV self-consumption may decrease stress on the grid thus easier integration of PV in the existing infrastructure. 
* Self-consumption by energy storage and demand side management (DSM). 
* EV for load balancing via smart charging and V2G. 
* PV adoption: costs, policy incentives, business models, and peer effects. 
* Diffusion forecast using the Bass model, which are S-curves for forecasing rather than ex-ante policy evaluation, which is possible with ABM allowing other factors in addition to the Bass model.
* Adoption patterns are determined by the spread of information among consumers. 
* The Bass model: innovators, imitators, the total number of adopters and the market size. 
* Supply, demand and self-consumption: electricity production by PV, electricity demand in addition to EV, and storage by EV. 
* Establishment of the geographical misfit between EV and PV diffusion and impact on energy systems. 
* EV diffusion lags behind PV diffusion leading to different supply and demand patterns for different regions which require different grid architectures. 

## Critique

* So simply Bass model. It may be necessary to use a complex model such as ABS including the systemic nature.
* Ecological fallacy. 
* To include PV system battery which will increase the self-consumption. 



# Litjens, G. B. M. A., Kausika, B. B., Worrell, E., and van Sark, W. G. J. H. M. (2018). “A spatio-temporal city-scale assessment of residential photovoltaic power integration scenarios.” Solar Energy, 174, 1185–1197.

> PV self-consumption (SCR) and self-sufficiencies (SSR) regarding EV and battery energy storage (BESS) for area dependent investments (grid extensoins and EV charging infra) and supporting policies of PV integration. 

## Findings 

* Due to PV, EV, and elec. heating, overloading will occur on the medium voltage grid (Sijm 2014). PV self consumption will lower medium voltage distribution grid losses and investments in cables and transformers. 
* PV yield timeseries created using python package PVLIB (Andrews et al. 2014). 
* EV charging options with 7.24 kWh per day and 11kW max. charging capacity: flattened charging profile, smart solar charging (van der Kam and van Sark 2015)
* Transit to heat pumps require electricity demand from natural gas depending on the heat resource (air or ground) and the building characteristics. 
* Smart solar charging of EV should focus on neighborhoods with large PV and low electricity consumption. 

# Araújo, K., Boucher, J. L., and Aphale, O. (2019). “A clean energy assessment of early adopters in electric vehicle and solar photovoltaic technology: Geospatial, political and socio-demographic trends in New York.” Journal of Cleaner Production, 216, 99–116.

> PV and EV diffusion regarding locational, political, and socio-demographic profiles using geo-spatial clustering and found financial means are the significant factors in early- in New York. 

## Findings

* Understanding attributes of early adopters is fundamental for decision-making in policies. 
* Networks can be instrumental in the adoption with 'core', early adopters for knowledge, and 'periphery', later adopters benefiting from knowledge spillovers. 
* Neighborhood effects, visibility influences for EV (Meshane et al. 2012).
* Solar diffusion correlated to higher home values (Dastrup et al. 2012) and less densely-populated areas (Graziano and Gillingham 2015).
* Financial means (income, home value) are most significant for diffusion.


_____

**3. Model** 

# Xu, Y., Fu, C., Kennedy, E., Jiang, S., and Owusu-Agyemang, S. (2018). “The impact of street lights on spatial-temporal patterns of crime in Detroit, Michigan.” Cities, 79, 45–52.

> Relationship between street light (environmental settings) and crime using GLS random-effects, a two-level hierarchical model

* Residential tenure and home ownership has impacts on the collective effort of communities to ensure social control (Sampson, Raudenbush and Earls 1997).
* Diversity measure: 1 - $\sigma$ pi^2 
* Residential instability: percentage of homes occupied by renters 
* Hierarchical model - level1: change over time within census tract, level2: IVs between census tracts. 

_____

**4. Energy Justice**

# Sovacool, B. K., and Dworkin, M. H. (2015). “Energy justice: Conceptual insights and practical applications.” Applied Energy, 142, 435–444.

> A synthetic energy justice framework as a conceptual, analytical, and decision-making tool with respect to Kantian ethics (individual rights), libertarian, pluralist, and utilitarianism (cumulative benefits) and welfare. 

## Findings 

* Conceptual: costs (imposed on communities unequally), benefits (how access to modern energy), procedures (inclusive decision making).
* Decision-making: availability (security of supply), affordability (stable prices), due process (stakeholder participation in policymaking process), good governance (information, accountability, transparency), sustainability (meeing the need of the present without compromising the future generations), intergenrational equity (present and future generation), intragenerational equity (different communities access to energy), responsibilty (environment, climate change, future generation, non-human species).
* Proper distribution (distributive justice, redistribution) and impartiality in decision-making (procedural justice, empowerment) are interconnected. 
* Energy justice should be the first to consider for consequences to the people the policies are intended to benefit as tech for salvation becomes a threat to our survival. 

# Fuller, S., and McCauley, D. (2016). “Framing energy justice: perspectives from activism and advocacy.” Energy Research & Social Science, 11, 1–8.

> Energy justice framework from activism and advocacy. 

## Findings 

* To date, energy justice was in terms of access to affordable energy, fuel poverty, and politics of energy infra. 
* To frame energy justice further from environmental and climate justice. 
* Production and consumption, distribution and procedure, contextual boundaries (what) and normative claims (how) in terms of temporal and spatial, articulation of vulnerability, and multi-scalar frames. 
* It was found that production (uneven distribution of production facilities) by environmental justice and consumption (affordable energy access) by income equality and low carbon transitions. 


# Jenkins, K., McCauley, D., Heffron, R., Stephan, H., and Rehner, R. (2016). “Energy justice: A conceptual review.” Energy Research & Social Science, 11, 174–182.

> Energy justice in terms of distributional, recognition and procedual in production and consumption regarding evaluative and normative reach. Futher suggesting non-activist origins of energy justice, engaging with economics, and uniting systems of production and consumption. What, who and how. 

## Findings

* Energy justice from an inter-disciplinary perspective as energy is a new center of gravity of justice scholars. 
* Energy security: supply of energy, availability and pricing; fuel poverty: energy vulnerability on distributional unfairness.
* Distribution: concern, where; uneven distribution of benefits, ills, and responsibilities. E.g. FiT transmits the cost (including infra of decentralized electricity supplies) to electricity consumers leading to distributional injustice for low-income communities. However, renewable transition allows just distribution of risks from electricity generation involving larger population compared to a centralized solution.
* Recognition: who it affects; losing the insights of marginalized social groups. Difference between global and local perceptions. 
* Procedure: strategies for remediation; decision-making, local knowledge mobilization, information disclosure, and institutional representation. 
* Energy policies have been dealing with only one section of energy system. 'Systems' thinking is needed including energy's externalities, transition to low-carbon sources from resource mining, transmission, and waste in social, economic, and environmental impacts. 
* Infra siting, subsidies, pricing (fuel poverty), and consumption indicators (smart meters) to address unequal distribution. 
* Energy as a socio-technical system, e.g. fuel cycle including oil well and agencies managing them. 
* Energy justice is pluralist; over a particular technology, application, location or point in time. 

# Heffron, R. J., and McCauley, D. (2017). “The concept of energy justice across the disciplines.” Energy Policy, 105, 658–667.

> Restorative justice appling in practice through the energy justice concept, education and engaging with economic policy-making.

## Findings

* The use of energy justice in practice by NGOs, early use in academia, then research literature were discussed. 
* Restorative justice to ensure energy justice applied in practice (from three tenets to applied principles) through environmental impact assessment (when the project built), social-license-to-operate (with the local communities over the life-span of the energy infra), and energy financial reserve obligation (to ensure the financial capacity to end the enregy infra). 
* From inter-disciplinary to multi- and trans-disciplinary based on practices of integration.
* 'Family resemblances' (overlapping and crisscrossing) similarities of environmental justice in 1970s and climate justice in 1990s in energy justice. 
* Related journals: energy policy, applied energy, energy and energy research and social science. 
* Economic-led policies (low-cost and efficient outcomes) lead to reliance on fossil fuels and low-carbon energy infra or a low-carbon economy become the secondary. 
* World Energy Council: energy security, environmental sustainability, energy equity (affordability and accessibility) to provide low-cost energy. 
* More just energy trilemma: economics, politics (energy security), environment (climate change mitigation) for energy law and policy (energy justice), e.g. green investment funds. 

# Sovacool, B. K., Burke, M., Baker, L., Kotikalapudi, C. K., and Wlokas, H. (2017). “New frontiers and conceptual frameworks for energy justice.” Energy Policy, 105, 677–691.

> New frontiers of future energy justice research: strengthening energy justice theory (Non-Western justice theories, non-anthropocentric justice, cross-scalar issues) and opportunities and tensions for energy justice in practice (business models, understanding the tradeoffs and exposing unjust discources). 

## Findings 

* Non-anthropocentric justice: anaimal-centrism, biocentrism and ecocentrism. 
* Cross-scalar issues: mobility justice in transend spatial scales. 
* Business models and treadeoffs: Justice has been considered expensive while some energy justice can make economic or financial sense (co-benefits). 
* Adding two more principles - resistance (standing up to injustice) and intersectionality (intertwined with socio-economic, political and environmental). 
* Energy system interventions are about political power, moral concerns over equity, social cohesion, due process and justice rather than just technology and economic development. 
* We need 'just aware' energy policy through avoiding externalities on marginalized and future generations for social welfare and minimizing environmental damage. 
* For equitable distribution of energy services among current and future generations as all people have a right to fairly access energy services. 

# Bouzarovski, S., and Simcock, N. (2017). “Spatializing energy justice.” Energy Policy, 107, 640–648.

> Addressing the lack of geography for the injustice of energy poverty.

## Findings 

* Energy poverty (fuel poverty, domestic energy deprivation) is the inability to attain a socially and materially necessiated energy services. 
* Spatial justice is about the geographical dimensions of inequality and inequity. 
* For uneven distribution, rather than focusing on drivers or consequences of energy poverty, this research is engaging theories of justice with geographic disparities in distribution and recognition. 
* Landscapes of material deprivation (infra, built environment), geographic underpinnings of energy affordability (energy prices, household incomes), vicious cycles of vulnerability (poor health due to material and socioeconomic spatial inequalities), and spaces of misrecognition (recognition injustice by not identifying or ignoring certain groups which affects household practices).
* Injustice originated from factors outside of an individual's control should be discussed in terms of structural geographical inequities. 
* Energy transitions are generators of geographically uneven social, political, and environmental displacements leading to vulnerability of particular groups. 
* Addressing energy poverty is the fundamental political duty. 
* Comprehensive, multi-scalar strategic approach spanning the whole energy system through less regressive means than carbon taxes or flat levies on energy bills. 
* Distributed energy systems have potential to reduce energy poverty (Sovacool et al. 2014). 
* To build urban resilience through relationship between energy poverty and socio-environmental contingencies (climate change, social segregation, energy provision). 

_____

**5. GIS & Social Equity**

# Walter, R., Evans, A., and Atherwood, S. (2016). “Addressing the Affordable Housing Crisis for Vulnerable Renters: Insights From Broward County on an Affordable Housing Acquisition Tool.” Housing Policy Debate, 26(1), 123–149.

> Identifying housing acquisition tools as affordable rental crisis with inequitable land-use patterns became a barrier to housing for the poor. 

## Findings 

* Housing mobility into neighborhoods with improved socioeconomic conditions yields benefits for low-income families (Crowley 2003).
* The placement of assisted housing in poor minority neighborhoods increases the concentration of poverty and contributes to further segregation (Turner, Popkin and Rawlings 2008).
* HCV for poverty deconcentration goals to address the significant costs to society caused by racial and economic segregation. 
* For property acquisition, unlike private sector focusing on economic factors, public sector includes social, culture, and environmental objectives (MacNair 2010).


# Wang, R., Walter, R. J., Arafat, A. A., Ding, X., and Naji, A. A. (2017). “Examining Neighborhood Opportunity and Locational Outcomes for Housing Choice Voucher Recipients: A Comparative Study between Duval County, Florida, and Bexar County, Texas: EXAMINING NEIGHBORHOOD OPPORTUNITY.” City & Community, 16(4), 421–446.

> Locational opportunity for holders of Housing Choice Voucher (HCV) or Section 8

## Findings 

* HCV created by HUD and administered by public housing authorities (PHAs) as moving to opportunity can help low-income households obtain self-sufficiency. 
* Living in low-poverty neighborhoods during childhood contributes to economic mobility later in life (Chetty and Hendren 2015). 
* Areas of opportunity - housing supply (housing affordability, availability, and quality), neighborhood accessibility (access to services), and neighborhood conditions (urban form). 
* Poverty deconcentration and economically and racially diverse neighborhoods became an explicit federal housing policy in the 2000s (Public Housing Agency Plans, HUD 2000). 
* As neighborhood quality increases, accessibility tends to decrease (Been et al. 2010). 
* Source of income antidiscrimination laws increases voucher utilization rates (Freeman 2012) and reduce neighborhood poverty rates for low-income households (Freeman and Li  2014).
* Policy makers are placing an enormous challenge on housing providers and low-income families if they factor only neighborhood conditions in. They need to consider housing supply and neighborhood accessibility. 

# Poruschi, L., and Ambrey, C. L. (2019). “Energy justice, the built environment, and solar photovoltaic (PV) energy transitions in urban Australia: A dynamic panel data analysis.” Energy Research & Social Science, 48, 22–32.

> Impact of built environment (urban planning policy) and FiTs (energy policy) on the installation of rooftop solar using a dynamic panel data model. Less dense built environments and more FiTs are related to more PV.

## Findings 

* Urban consolidation can lower resident's energy consumption by efficient transportation, shorter networks, increasing shared walls, etc. 
* Infill based urban consolidation can act as an obstacle to the uptake of RE technologies.
* Equity questions about access benefits of solar such as FiTs. 
* For equitable energy policy, relationship between built environment change and how electricity is generated and used is important regarding urban planning. 
* High-rise multi-unit developments detract from PV installations. 
* FiTs are a form of regressive taxation benefiting wealthier households resulting in taxation on low-income housholds leading to energy inequalities.
* Energy and societal transformation has the potential to amplify equity issues as the distribution of benefits seems to be localised in higher income areas. 
* Future studies: policy outcomes for specific groups (renters, low-income, etc.).

# Lukanov, B. R., and Krieger, E. M. (2019). “Distributed solar and environmental justice: Exploring the demographic and socio-economic trends of residential PV adoption in California.” Energy Policy, 134, 110935.

> DES (having community benefits such as grid resilience and lower grid emissions) is correlated with socioeconomic variables, health, environmental and demographic indicators. 

## Findings 

* Higher residential utility costs can place a disproportionate burden on low-income households. 
* Energy burden disparities as fuel poverty and energy insecurity for the basic energy needs. 
* Regulatory agencies have started to consider social equity, health, and environmental foctors in policy decision-making. 
* PV adoption rates in disadvantaged communities (DACs) defiend by CalEnvironScreen (CES) and environmental justice (EJ) communities. 
* There are still equity issue despite the two low-income programs, Single-Family Affordable solar Homes (SASH) and Multifamily Afofrdable Solar Housing (MASH). 
* Key drivers for PV adoption are income and home ownership (Barbose et al. 2018). 
* More granular data on the houshold level is necessary to explore whether trends community-based or household-based. 
* The benefits of PV on low-income households: addressing energy disparities through net metering and FiTs, environmental and health co-benefits; improving resilience with storage (Krieger et al. 2016). 
* Solar adoption gap between EJ communities and others will likely continue to increase.
* New programs such as SOMAH, DAC-SASH and Green Tariff programs (electricity bill discounts for DACs and community solar) are still in their nascent stage.
* Community Choice Aggregations (CCA) with carve-outs for LMI customers who live far from resources not in the vicinity. 
* Future research: social diffusion effects, household level data.

_____

**6. Shared solar**

# Augustine, P., and McGavisk, E. (2016). “The next big thing in renewable energy: Shared solar.” The Electricity Journal, 29(4), 36–42.

> Need to address political and economic barriers for full-scale adoption of community solar

## Findings

* Barriers: homeownership, multi-unit housings, lack of roof space, soft costs (lack of info., complex application, inspection requirements, variou net metering and incentives)
* Features: economies of scale for the large systems, updating IT for virtual net metering, underestimating the time and cost for customer education and marketing.
* Needs: 1. guidance, 2. viable model for low-income households, 3. access to tax credits (e.g., modified accelerated cost recovery system (MACRS) which could reduce the costs on the order of 50% with investment tax credit (ITC)) while needing passive income and tax basis or to partner with a tax equity investor justifying the transaction costs (for due diligence and contracting), renewable energy certificates (REC), which utilities are required, 4. virtual net metering (utilities are against it since transmission, distribution, reliability are not accounted for) and solar tariffs, and 5. transferring subscriptions. 
* Ownership: utility, a third-party, or a special entity
* subscription: buy panels, lease panels, invest, and buy energy/capacity


# Chan, G., Evans, I., Grimley, M., Ihde, B., and Mazumder, P. (2017). “Design choices and equity implications of community shared solar.” The Electricity Journal, 30(9), 37–41.

> How design decisions affect access to solar and the equity of cost and benefit sharing for community shared solar (CSS). 

## Findings 

* CSS with virtual net metering, 1. capturing economies of scale, 2. inclusive to customers, 3. addressing existing inequities, and 4. providing opportunities for community-level mobilization of resources. 
* CSS objectives: 1. increase solar deployment, 2. broaden access to the benefits of solar (Chwastyk and Sterling 2015). 
* Ownership, subscription, site selection, subscriber enrollment, program management. 
* Utility-owned: REC, RPS, rebates, incentives, MACRS.
* Third-party or SPE program: PPA with utility in charge of distribution and billing. Concerns on not being able to capture tax benefits as they should be tax equity. 
* As ratepayers and taxpayers support the CSS tariff, credit screen for joining CSS may cause inequity by excluding LMI households. 
* LMI households may subsidize higher-income households who own solar. 
* Pay-as-you-go would be easier to set up the CSS than paying up-front (Trabish 2017). 
* Access considerin equity: energy, ownership of RE credits, the opportunity of owning solar, and financial benefits. 
* Costs and benefits of energy infra investments are distributed across ratepayers (customers), taxpayers (incentives), and utility shareholders. 
* Future studies: Impact of CSS on equity of distribution of costs and benefits, what policy design options to make CSS more effective and equitable. 

# Ptak, T., Nagel, A., Radil, S. M., and Phayre, D. (2018). “Rethinking community: Analyzing the landscape of community solar through the community-place nexus.” The Electricity Journal, 31(10), 46–51.

> The concept of community as it was misrepresentated through community washing. 

## Findings 

* Community: a group of people who engage and interact in some manner, share some form of identity and/or connection to a specific geographic feature or defined area. 
* CS porject models: utility-sponsored, SPE, and non-profit. 
* CS (designed to increase access to solar energy and to reduce upfront costs for participants; allowing a group of citizens to invest in solar that isn't affixed to their own residence and thus avails this technology to a wider demographic (Augustine 2015)) leads to opportunities for new forms of engagement with local communities. 
* The concept of place has not been examined in CS development in the US. 
* Physical proximity to wind turbines are not good predictors of public opposition to them than social influence and community perceptions (Devine-Wright 2005). 
* Appropriation of CS by solar developers through liking to spatially defined communities when they are not. 
* Community should be defiend in regard to CS or replaced by shared solar.
* Questions about tangible outcomes or benefits of CS to communities of shared spatial characteristics beyond economic metrics. 
* Future studies: if the CS project values "community" by enhancing a sense of community, if the CS provides benefits beyond reduced tariffs to better understand the distribution of benefits. 
* Utilities to promote affordability programs while new models of governance and policy frameworks such as PPP are necessary e.g. PV and Powerwall batteries were financed by the sale of electricity while promoting the sense of community friendly. 

_____

**7. Renewable Energy**

# Toward 100% RE Pathways: Key Research Needs

* Energy transition for decarbonization due to climate change: demand side participation, battery storage, and decentralization with respect to variable renewables considering cost-reliability tradeoff as it is easy to go 100% with high cost and low reliability. 
* Issues in supply-demand balance reliably as RE does not have active generation and demand connected. 
* Resource adequacy: Power plants get paid by providing capacity. There are requirements - system, local and flexible capacity. More diverse and less correlated RE sources, storage and demand participation are needed. 
* Flexibility and the provision of services are an operational while adequacy is a planning challenge: e.g. improved forecasting, new operating tools ensuring stability of the system, probabilistic mindset, storage, data, and coordiation between systems. 
* Market: price volatility due to variable RE requires investment for flexibility. 
* Issues in voltage and frequency control as RE is non-synchronous with no inherent inertial response. 
* Distribution: Coordination with transmission system is important. 
* Future studies: 1. change in the synchronous nature of the electricity system will affect the core technologies with its control and protection. 2. change in need of reliability and demand side will affect adequacy (planning), flexibility (operation), and supply-demand balance. 

# Michaud, G. (2018). “Deploying solar energy with community choice aggregation: A carbon fee model.” The Electricity Journal, 31(10), 32–38.

> Carbon fee model for the development of solar in CCA

* PV benefits: GHG emission reductions, health benefits, and decreasing water consumption.
* High upfront cost for PV could be addressed with community choice aggregation (CCA) as electric service provider, who yet end up purchasing RECs from elsewhere while trying to source RE. 
* Deregulation may lead to less grid reliability with increased competition (Nadler 2013) which suspended some state to have the market restructuring (deregulation). 
* Distributed PV may eliminate transmission and line losses (Teng et al. 2013) and offset peak demand and stabilize the local grid (Pitt & Wang 2018). 
* CCA in CA offers a higher RE than any other IOUs (McMahon 2018). 
* A unique model: SOPEC (a CCA) in Ohio with a carbon fee installed PV. CCA could be a solution for those communities without a municipal electric utility. 



_____

# Note

## To check 

* Given that consumer-owned renewable electricity, such as from rooftop PV, does often benefit from not paying for the grid infrastructure, the financing necessary for improvement of the grid will be challenging. Therefore, how the grid will be financed when renewables are expanded is also an important topic for future research.
* Why Seattle or WA? Include the background about PV in Seattle or WA
* The difference of degree of PV adoptions for early adopters (green life style) and mainstream consumers (on the verge of grid parity - profitability)
* Early adoption stage - financial incentives as well as peer effects for increasing adoption. 
* Relationship between PV and EV adopters. PV adopters may consider EVs (Rai et al. 2016)

## Research flow 

* To identify drivers and barriers for diffusion. 
* To have FA for multi-collineaerity, temporal, spatial models for spatial autocorrelation.
* Spillover effects (social contagion), local advocay, and business models on diffusion to be addressed. 
* Variables of individual analysis: the number of PV around neighbor, clustering group, irradiation, the number of previous PV, 
* Different distribution patterns between PV and EV. 
* Mixture of clean policies and electricity network planning.
