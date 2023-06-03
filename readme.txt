WHAT IS MACHINE LEARNING?
    Formal Definition:
        •   A machine learning program is said to learn from experience E with respect to some class of tasks T and
            performance measure P, if its performance at tasks in T, as measured by P, improves with experience E

conda install scikit-learn
pip install scikit-learn

Every algorithm is exposed in scikit-learn via an "Estimator"
First you'll import the model, the general form is:
from sklearn.<family> import <Model></Model>
    For example:
        from sklearn.linear_model import LinearRegression
    

Estimator parameters: All the parameters of an estimator can be set when it is instantiated, and have suitable default values.
You can use Shift+tab in jupyter to check the possible parameters.

For example:
model = LinearRegression(normalize=True)
print(model)

LinearRegression(copy_X=True, fit_intercept=T, normalize=True)