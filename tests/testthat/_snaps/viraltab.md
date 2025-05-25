# viraltab() works

    Code
      viraltab(traindata, semilla, target, viralvars, logbase, pliegues, repeticiones,
        rejilla, rank_output = TRUE)
    Message
      i Creating pre-processing data to finalize unknown parameter: mtry
    Condition
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
      Warning:
      Using `all_of()` outside of a selecting function was deprecated in tidyselect 1.2.0.
      i See details at <https://tidyselect.r-lib.org/reference/faq-selection-context.html>
    Output
                          wflow_id              .config .metric   mean std_err n
      1             normalized_KNN Preprocessor1_Model1    rmse 126.56    4.20 2
      2             normalized_KNN Preprocessor1_Model1     rsq   0.75    0.03 2
      3         simple_CART_bagged Preprocessor1_Model1    rmse 143.53    3.09 2
      4         simple_CART_bagged Preprocessor1_Model1     rsq   0.61    0.04 2
      5              simple_Cubist Preprocessor1_Model1    rmse 156.72   28.24 2
      6              simple_Cubist Preprocessor1_Model1     rsq   0.58    0.13 2
      7                  simple_rf Preprocessor1_Model1    rmse 156.99    9.59 2
      8                  simple_rf Preprocessor1_Model1     rsq   0.75    0.06 2
      9              full_quad_KNN Preprocessor1_Model1    rmse 167.49   16.21 2
      10             full_quad_KNN Preprocessor1_Model1     rsq   0.53    0.11 2
      11     normalized_SVM_radial Preprocessor1_Model1    rmse 232.88   10.02 2
      12     normalized_SVM_radial Preprocessor1_Model1     rsq   0.62    0.08 2
      13 normalized_neural_network Preprocessor1_Model1    rmse 249.62   44.67 2
      14 normalized_neural_network Preprocessor1_Model1     rsq   0.22    0.15 2
      15      full_quad_linear_reg Preprocessor1_Model1    rmse 254.97  111.41 2
      16      full_quad_linear_reg Preprocessor1_Model1     rsq   0.32    0.31 2
      17       normalized_SVM_poly Preprocessor1_Model1    rmse 440.08  257.78 2
      18       normalized_SVM_poly Preprocessor1_Model1     rsq   0.20    0.18 2
               preprocessor            model rank
      1              recipe nearest_neighbor    1
      2              recipe nearest_neighbor    1
      3  workflow_variables         bag_tree    2
      4  workflow_variables         bag_tree    2
      5  workflow_variables     cubist_rules    3
      6  workflow_variables     cubist_rules    3
      7  workflow_variables      rand_forest    4
      8  workflow_variables      rand_forest    4
      9              recipe nearest_neighbor    5
      10             recipe nearest_neighbor    5
      11             recipe          svm_rbf    6
      12             recipe          svm_rbf    6
      13             recipe              mlp    7
      14             recipe              mlp    7
      15             recipe       linear_reg    8
      16             recipe       linear_reg    8
      17             recipe         svm_poly    9
      18             recipe         svm_poly    9

