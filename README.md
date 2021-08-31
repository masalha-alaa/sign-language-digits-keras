# Sign Language Digits Classification
In this project I created a simple CNN with data augmentation to classify sign language hand digits \[[dataset source](https://github.com/ardamavi/Sign-Language-Digits-Dataset)\]. With about 20 epochs, the model achieved a 98% accuracy on the test set (I set 30 epochs, and used an "early stopping" callback which has stopped the model just when it started to converge).

![accuracy and loss](https://user-images.githubusercontent.com/78589884/131554895-dba10562-9ac4-4344-b0ff-f6f1924c38fd.png)

## Test Examples
A few prediction examples (from the test set) can be seen in the following snapshot:

![test examples](https://user-images.githubusercontent.com/78589884/131555003-09e59e33-4903-4954-8d03-8f2efab2a988.png)

For a full walkthrough of the code, please head over to the [sign_language_digits.ipynb](https://github.com/masalha-alaa/sign-language-digits-keras/blob/master/sign_language_digits.ipynb) notebook in the root directory of this repo.
