# simulation-
import pandas as pd
from matplotlib import pyplot as plt
import matplotlib.pyplot as figure

data=pd.read_csv('yourFileName.csv')
plt.plot(data.population,data.year)
plt.title("World Population By Year")
plt.xlabel("Population")
plt.ylabel("Year")
plt.legend(["Population increase"])
plt.savefig('data.jpg', dpi = 500)
plt.show()
plt.close()
