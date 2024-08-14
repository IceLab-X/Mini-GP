# Model Comparison and Regression Test

- **Model_comparison.py:** A Python script that compares the performance of different GP models on various synthetic datasets, including periodic, warped, and polynomial. The default models are set as autoGP and its base model vsgp.

  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison_autoGP.png" alt="Model Comparison for autoGP and vsgp" width="400"/>
  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison_warped.png" alt="Model Comparison for autoGP and vsgp" width="400"/>

- **Regression_test.py:** A Python script that tests the accuracy and training speed on different sizes of training sets. The results are stored in result1.csv and result2.csv.

- **result1.csv:** The result of the regression test for different training set sizes.

  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison%20Accuracy.PNG" alt="Model Comparison -- Accuracy" width="400"/>
  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison%20Speed.PNG" alt="Model Comparison -- Speed" width="400"/>

- **result2.csv:** The result of the regression test for different numbers of inducing points.

  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison%20Accuracy2.PNG" alt="Model Comparison -- Accuracy 2" width="400"/>
  <img src="https://github.com/IceLab-X/Mini-GP/blob/e8989225a03adad60a1f1b430a360cb0bf8fecc1/core/Model_comparison&Regression_test/Model_comparison%20Speed2.PNG" alt="Model Comparison -- Speed 2" width="400"/>