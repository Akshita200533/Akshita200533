import pandas as pd


dataFrame = pd.read_csv("item sheet - Sheet1.csv")
print("Missing value of each column",dataFrame)


dataFrame[0:6].fillna(0,inplace=True)
print(dataFrame)
