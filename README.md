# Elasticnets, etc.
Elastic nets, lasso, ridge, examples, etc. This example is from Tony Fischetti, but could easily be adapted to a larger dataset with Yield as response. 
One of things I don't really quite yet understand is whether these class of models permit interaction (especially important for gene-by-environment component - or does this just go into the residual error term?).
I reviewed the penalties for each type of model, and also figured out that in some cases OLS can outperform elasticnets and ridge/lasso regressions for MSEs, but elasticnets almost always are as good as ridge or lasso.
My questions at this point are:
- How do these classes of models incorporate interactions?
- Why does OLS on occasion outperform them for MSEs?
- Elasticnets penalty - I still don't quite get the penalization theory as well as with ridge or lasso and shrinkage, so this is something to think about.
