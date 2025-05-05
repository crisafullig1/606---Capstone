# 606---Capstone

Each model should be pre - set to just download the data files to run on.

For LASER:

  EN/ES - The necessary files are preloaded where they need to be called. They will be the train.txt and test.txt files
  ML/EN - Again, all is preloaded for the code to just run. They will be enma_natural_train.txt and enma_natural_test.txt

For XLM:

  There will be the following, where each file needs to be inputted after it is downloaded: 

  train_texts, train_labels = read_data('     .txt')
  test_texts, test_labels = read_data('       .txt')

  For EN/ES: first train on the english_data.txt and test on the test.txt file, then train on spanish_data.txt and test on the test.txt file
  For ML/ES: first train on the english_data.txt and test on the enma_natural_test.txt, then train on the malayalam_clean.txt and test on the enma_natural_test.txt
