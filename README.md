pd.read_csv('.csv')
df.isnull().sum()
*EDA*
drop unique 
  df.drop(labels['id'],axis =1)
check duplicates
  df.duplicated().sum()    
  df.drop_duplicates
segregate numerical and categorical features
  numerical_columns=df.columns[df.dtypes!='object']
  categorical_columns=df.columns[df.dtypes=='objects']
df[categorical_colums].describe()
df['cut'].unique()
df['cut'].value_counts()


