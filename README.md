Executive Summary:

This research paper presents a comprehensive time series analysis of air quality data for Delhi from 2018 to 2023.
The study examines temporal trends, seasonal patterns on pollutant levels, focusing on key pollutants such as
PM2.5 (ug/m3), PM10 (ug/m3), SR (W/mt2), AT (degree C). Predictive modeling technique ARIMAX was utilized
to forecast future air quality. The best-performing model was selected based on AIC and SBC scores, ensuring
optimal balance between model fit and complexity, and demonstrating robust predictive capabilities. Insights from
this study can guide public health strategies and policy decisions aimed at improving air quality.

Introduction:

Air pollution in India has become a pressing issue with far-reaching consequences for public health, the
environment, and the economy. Among the cities most affected by air pollution, Delhi stands out, with particulate
matter, nitrogen dioxide, sulfur dioxide, and carbon monoxide levels consistently surpassing safe limits. This
project seeks to analyze the air quality trends in Delhi between 2018 and 2023, a period of significant
environmental and policy changes. By leveraging time series data from the Central Pollution Control Board
(CPCB), the study aims to uncover patterns, trends, and potential seasonal variations in air quality, helping to
inform future environmental interventions.

Through this study, we aim to answer critical questions related to the temporal dynamics of air pollution, the
influence of seasonal factors, and the effectiveness of governmental policy measures. Notably, the project will
explore how specific policies—such as the introduction of odd-even schemes or the impact of COVID-19
lockdowns—have affected pollutant levels. Additionally, the analysis will contribute to the development of
predictive models that can forecast air quality trends, supporting decision-making for better public health and
environmental protection strategies. By identifying key pollutants and understanding their seasonal behavior, this
research will enhance awareness about air quality issues and guide policymakers in the formulation of more
effective pollution control measures.

Key Variables in the Dataset:

The dataset includes several key variables that provide valuable insights into air quality and environmental
conditions in Delhi over the period of 2018 to 2023. The four key variables specifically used for this analysis
are:

1. PM2.5 (µg/m³):  
Description: PM2.5 refers to particulate matter that is smaller than 2.5 micrometers in diameter. These
tiny particles can be inhaled deep into the lungs and enter the bloodstream, causing severe health
problems such as respiratory diseases, cardiovascular issues, and premature death.

Significance: PM2.5 is considered one of the most dangerous pollutants due to its ability to penetrate
deep into the respiratory system. It is a major concern for public health, especially in urban areas with
high traffic and industrial emissions. In the dataset, the concentrations of PM2.5 are measured in
micrograms per cubic meter (µg/m³).

3. PM10 (µg/m³):
Description: PM10 refers to particulate matter that is smaller than 10 micrometers in diameter.
Although larger than PM2.5, these particles can still cause significant health problems, especially for
people with pre-existing lung conditions like asthma. PM10 is often produced by road dust, industrial
emissions, and other sources.

Significance: PM10 pollution is harmful to human health, leading to respiratory problems, aggravating
asthma, and even contributing to cardiovascular diseases. The concentration of PM10 in the air is
measured in micrograms per cubic meter (µg/m³), and its trends are important for monitoring air
quality in urban and industrial zones.

4. SR (Solar Radiation, W/m²):
Description: Solar radiation (SR) refers to the amount of solar energy received per unit area on the
Earth's surface, measured in watts per square meter (W/m²). Solar radiation affects various atmospheric
processes and can influence pollution levels by affecting weather patterns, including temperature and
wind.

Significance: Solar radiation is important in the context of air quality because it plays a role in the
formation of secondary pollutants like ozone, especially in the presence of other pollutants such as
NOx. The intensity of solar radiation can also be linked to seasonal changes in air quality, where higher
radiation levels in the summer months could lead to an increase in air pollution formation.

5. AT (Ambient Temperature, °C):
Description: Ambient temperature (AT) refers to the temperature of the surrounding environment,
measured in degrees Celsius (°C). It is an important meteorological variable that can influence both the
physical properties of air pollutants and the atmospheric conditions under which they are dispersed or
concentrated.

Significance: Temperature can impact the concentration and behavior of various pollutants. For example,
higher temperatures can increase the rate of chemical reactions in the atmosphere, leading to higher levels
of pollutants like ozone. Temperature variations also affect atmospheric pressure and wind patterns,
which influence the dispersion of pollutants. Understanding temperature trends alongside pollutant data
can help identify seasonal patterns and improve the interpretation of air quality data.
