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
      3                  simple_rf Preprocessor1_Model1    rmse 156.99    9.59 2
      4                  simple_rf Preprocessor1_Model1     rsq   0.75    0.06 2
      5              simple_Cubist Preprocessor1_Model1    rmse 157.27   28.79 2
      6              simple_Cubist Preprocessor1_Model1     rsq   0.59    0.12 2
      7              full_quad_KNN Preprocessor1_Model1    rmse 167.49   16.21 2
      8              full_quad_KNN Preprocessor1_Model1     rsq   0.53    0.11 2
      9      normalized_SVM_radial Preprocessor1_Model1    rmse 232.88   10.02 2
      10     normalized_SVM_radial Preprocessor1_Model1     rsq   0.62    0.08 2
      11 normalized_neural_network Preprocessor1_Model1    rmse 249.62   44.67 2
      12 normalized_neural_network Preprocessor1_Model1     rsq   0.22    0.15 2
      13      full_quad_linear_reg Preprocessor1_Model1    rmse 254.97  111.41 2
      14      full_quad_linear_reg Preprocessor1_Model1     rsq   0.32    0.31 2
      15       normalized_SVM_poly Preprocessor1_Model1    rmse 440.08  257.78 2
      16       normalized_SVM_poly Preprocessor1_Model1     rsq   0.20    0.18 2
               preprocessor            model rank
      1              recipe nearest_neighbor    1
      2              recipe nearest_neighbor    1
      3  workflow_variables      rand_forest    2
      4  workflow_variables      rand_forest    2
      5  workflow_variables     cubist_rules    3
      6  workflow_variables     cubist_rules    3
      7              recipe nearest_neighbor    4
      8              recipe nearest_neighbor    4
      9              recipe          svm_rbf    5
      10             recipe          svm_rbf    5
      11             recipe              mlp    6
      12             recipe              mlp    6
      13             recipe       linear_reg    7
      14             recipe       linear_reg    7
      15             recipe         svm_poly    8
      16             recipe         svm_poly    8

