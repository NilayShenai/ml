import pandas as pd

df = pd.DataFrame({
    'Outlook': ['Sunny', 'Sunny', 'Rainy', 'Rainy', 'Overcast', 'Sunny'],
    'Wind': ['Weak', 'Strong', 'Weak', 'Strong', 'Weak', 'Weak'],
    'Play': ['No', 'No', 'Yes', 'Yes', 'Yes', 'No']
})

print(df)
