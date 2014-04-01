# LHCb matplotlibrc

A matplotlibrc that produces plots close to the official LHCb style.

The following options need to be manually specified in your python script:
```python
plt.xlabel(..., ha='right', x=1)
plt.ylabel(..., ha='right', y=1)
plt.legend(loc='best')
plt.minorticks_on()
```

In order to add a proper "LHCb Simulation" text box, use:
```python
plt.text(x, y, 'LHCb Simulation', {'size': 28})
```
