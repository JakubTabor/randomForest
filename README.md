# randomForest
# First i load four images """for i in range(4)""" of numbers low quality image """digits.images[i]""" and plot them 
# I get the numerical data because it interest me the most """pd.DataFrame(digits.data"""
# Then i create new column "target" """df['target']=digits.target""" to see where are my numbers
# Next i split my data into target and rest: "X" and "y" 
# I get my train_test_split and test_size at (0.2)
# From "ensemble" i get my "RandomForestClassifier" and set number of "trees" at (40) """n_estimators=40"""
