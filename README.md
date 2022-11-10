###Heatmap*******
plt.figure(figsize=(10,5))
c=df.corr()
//syntax//-------sns.heatmap(c)
sns.heatmap(c,cmap='BrBG',annot=True)
c
