# Big Header
paragraph
### Add an Image

![Alt Text of the image](https://octodex.github.com/images/yaktocat.png)

### ADD SOME CODE
Now i put some python code in here
```
from mpl_toolkits import mplot3d

fig = plt.figure(figsize = (10,10))
ax = plt.axes(projection = '3d')

ax.grid()
t = np.arange(0,10*np.pi,np.pi/50)
x = np.sin(t)
y = np.cos(t)
ax.plot3D(x,y,t)

ax.set_title("3D Parametric Plot")
ax.set_xlabel("x", labelpad=20) # <- Use labelpad to avoid overlapping
ax.set_ylabel("y", labelpad=20)
ax.set_zlabel("t", labelpad=20)
```
