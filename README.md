In this project we have build voice Controlled Ordering and Billing System of
BUET Cafeteria.The system will take two speech signals from a user, one for
the name of the item and one for the quantity, and compare them to previously
recorded inputs from different users.When the system finds a suitable match, it
determines which item the person wishes to purchase as well as the quantity.
The idea is to start by extracting useful features from raw speech data collected
from various users. The Mel-Frequency Cepstral Coefficients algorithm was used
in this paper to extract these features, which involves calculating coefficients
from user audio data that are unique to each user. Then, using the K-NN
Algorithm, these coefficients are compared to new MFCC coefficients extracted
from audio data from a new user. K-nearest neighbors (KNN) algorithm uses
‘feature similarity’ to predict the values of new data points which further means
that the new data point will be assigned a value based on how closely it matches
the points in the training set. This paper’s precision is moderate.
