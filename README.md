


import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(-5, 5, 200)  # 200 puntos entre -5 y 5
y = np.sin(x)

plt.plot(x, y, color='blue', linewidth=2)
plt.grid(True)
plt.title('Gráfica de y = sin(x)')
plt.xlabel('x')
plt.ylabel('y')
plt.axhline(0, color='black', linewidth=1)  # línea horizontal en y=0
plt.axvline(0, color='black', linewidth=1)  # línea vertical en x=0
plt.legend(['y = sin(x)'])
plt.show()

