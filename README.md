# Spy-Rocket-analysis
DATA EXPLORATION
Understand the characteristics of given fields in the underlying data such as variable
distributions, whether the dataset is skewed towards a certain demographic and the
data validity of the fields.
Identify limitations surrounding the data and gather external data which may be
useful for modelling purposes. This may include bringing in ABS data at different
geographic levels and creating additional features for the model. 
Exploration of interactions between different variables through correlation analysis
and look out for multicollinearity by creating interaction variables. An example of this
correlation may occur between independent variables age and tenure – i.e. people
of the older brackets will have a longer tenure.
Furthermore, transformation of required data so that it is in an appropriate format for
analysis. This may include steps such as ensuring that the data types are
appropriate and rolling data up to an aggregated level. Or, joining in already
aggregated ABS data at a geographic level to create additional variables.
MODEL DEVELOPMENT
Determine a hypothesis related to the business question that can be answered with
the data. Perform statistical testing to determine if the hypothesis is valid or not.
 Other fields that may be engineered include ‘High Margin Product’
which may be an indicator of whether the product purchased by the customer is in a
high margin category in the past three months based on the fields ‘list_price’ and
‘standard cost’.
 Additionally, this may include thoughts around determining what the
predicted variable actually is. For example, are results predicted in ordinal buckets,
nominal, binary or continuous. Test the performance of the model using factors
relevant for the given model chosen (i.e. residual deviance, AIC, ROC curves, R
Squared). Appropriately document model performance, assumptions and limitations.
INTEPRETATION AND REPORTING
Visualisation and presentation of findings. This may involve interpreting the
significant variables and co-efficient from a business perspective. These slides
should tell a compelling storing around the business issue and support my
case with quantitative and qualitative observations.
