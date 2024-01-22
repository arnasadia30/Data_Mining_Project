Please open the Final.ipynb file
To run the codes please change the path of the read.csv to where the files census-income.data.csv and census-income.test.csv  are located

For eg : change C:/Users/Hitesh Chordiya/Desktop/DESKTOP FILES/Fordham 2nd semester/Data Mining/Project/census-income.data.csv to /Manali_Chordia_CS5790_Project/census-income.data.csv

census_income_train = pd.read_csv('C:/Users/Hitesh Chordiya/Desktop/DESKTOP FILES/Fordham 2nd semester/Data Mining/Project/census-income.data.csv', names=['age', 'workclass', 'wgt', 'education', 'education_id', \
                                      'marital_status', 'occupation', 'relationship', 'race', 'sex', \
                                      'capital_gain', 'capital_loss', 'hours_per_week', 'native_country', 'income'])

For eg : change C:/Users/Hitesh Chordiya/Desktop/DESKTOP FILES/Fordham 2nd semester/Data Mining/Project/census-income.data.csv to /Manali_Chordia_CS5790_Project/census-income.test.csv

census_income_test = pd.read_csv('C:/Users/Hitesh Chordiya/Desktop/DESKTOP FILES/Fordham 2nd semester/Data Mining/Project/census-income.test.csv', names=['age', 'workclass', 'wgt', 'education', 'education_id', \
                                      'marital_status', 'occupation', 'relationship', 'race', 'sex', \
                                      'capital_gain', 'capital_loss', 'hours_per_week', 'native_country', 'income'])