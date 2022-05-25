# draw a plot
code is below
```import seaborn as sns
import matplotlib.pyplot as plt
#set style
sns.set_theme(style="darkgrid",color_codes="true")
#load data set
flower=sns.load_dataset("iris")
#draw a line plot
sns.lineplot(x="sepal_length",y="sepal_width",data=flower)
#adding title
plt.title("Flower fig 1 ")
plt.show()

```