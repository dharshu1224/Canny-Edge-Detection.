# Canny-Edge-Detection.

# Name:Dharshini.S
# Reg no:212224230061

# program:
```
import cv2
import matplotlib.pyplot as plt
img = cv2.imread("C:\\Users\\admin\\dharsh.jpg")
blurred =cv2.GaussianBlur(img, (5,5),0)
edges = cv2.Canny(blurred, 50, 150)
plt.figure(figsize=(10,5))
plt.subplot(121),plt.imshow(img, cmap='gray')
plt.title('Original Image'), plt.axis('off')
plt.subplot(122),plt.imshow(edges, cmap='gray')
plt.title('Detected Edges'), plt.axis('off')
plt.show()

```

# output:


<img width="1106" height="647" alt="image" src="https://github.com/user-attachments/assets/aafdfeaf-9fcc-4925-9991-bdcad42a5169" />

