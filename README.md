# code12



from pandas import read_csv
import datetime
from matplotlib import pyplot
from matplotlib import pyplot as plt
from colorama import init, Fore, Back, Style
from termcolor import colored  
#def parser(x):
    #return datetime.strptime('190'+x, '%Y-%m')
  
series = read_csv('code.csv', header=0, index_col=0, squeeze=True)
series.plot()
plt.xlabel('date').set_color('red')
plt.ylabel('buy').set_color('blue')

pyplot.show()
