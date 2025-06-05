---
width: "3000"
height: "1920"
progress: "true"
---

# SEGURIDAD EN REDES

Adán Alvarez, Christopher Mendoza, Josue Vera

## Capítulo 8 (5ª Edición)

### Secciones 8.1 - 8.3

Andrew S. Tanenbaum, David J. Wetherall

---

<div style="display: flex; gap: 2em;">
    <img src="images/Pasted image 20250529160143.png" alt="" style="max-width: 45%; height: auto;">
    <img src="images/Pasted image 20250529160119.png" alt="" style="max-width: 45%; height: auto;">
</div>

<img src="images/Pasted image 20250529171706.png" alt="" style="display: block; margin: 2em auto; max-width: 80%; height: auto;">

---

<img src="images/Pasted image 20250529160259.png" alt="" style="max-width: 80%; height: auto;">

---

# CIA

---

<img src="images/Pasted image 20250529113103.png" alt="" style="max-width: 80%; height: auto;">

---

# Confidencialidad

---
# Integridad

---

# Disponibilidad

---
## Authenticity
## Accountability

---

<img src="images/Pasted image 20250529103344.png" alt="" style="max-width: 80%; height: auto;">

---

# Criptografía

---

# $C = E_K(P)$

---

# $P = D_K(C)$

---

# $P = D_K(E_K(P))$

---

<img src="images/Pasted image 20250529115811.png" alt="" style="max-width: 50%; height: auto;">

---

<img src="images/deepseek_mermaid_20250529_79bd43.png" alt="" style="max-width: 80%; height: auto;">

---

# Sistemas de cifrado por sustitución

En un sistema de cifrado por sustitución, cada letra o grupo de letras se reemplazan por otra letra o gru­po de letras para disfrazarla. Uno de los sistemas de cifrado más viejos conocido es el sistema de cifrado de César, atribuido a Julio  César. En este método, a se vuelve D, b se vuelve E, c se vuelve F, ... , y z se vuelve C. Por ejemplo, ataque se vuelve DWDTXH. En nuestros ejemplos, el texto plano se presentará en minúsculas y el texto cifrado en mayúsculas.

---

### Cifrado por sustitución monoalfabética

## $26! ≈ 4 \times 10^{26}$

<img src="images/Pasted image 20250529161303.png" alt="" style="max-width: 80%; height: auto;">

---

### Cifrado por transposición

<img src="images/Pasted image 20250529161416.png" alt="" style="max-width: 80%; height: auto;">

---

# Criptografía cuántica

<img src="images/Pasted image 20250529174505.png" alt="" style="max-width: 80%; height: auto;">

---

BB84 (Bennet y Brassard, 1984).

---

## 1. Incondicionalmente Segura

## 2. Computacionalmente Segura

---
# Clave Simétrica
---

<img src="images/deepseek_mermaid_20250529_7049ae.png" alt="" style="max-width: 80%; height: auto;">

---

# DES (Estándar de Encriptación de Datos)
- Enero de 1977 por **IBM**
- El Original ya no es útil, es vulnerable por **Fuerza Bruta**
- Para Archivos no secretos del Gobierno 
---
# FUERZA BRUTA
---
# DES
Poseía una clave de **56 bits**, su estructura consta de **19 etapas**, iniciando con una permutación fija, <split ></split>luego pasa por 16 iteraciones idénticas las cuales aplican sustituciones, permutaciones y <split></split>operaciones XOR con subclaves derivadas de la clave original, para culminar intercambia los 32 bits izquierdos y derechos <split ></split>
Terminando con deshacer la permutación fija inicial.
___
---
# Triple DES
- Enero de 1979 por **IBM**
- Dos Claves y tres etapas (EDE)
- 112bits
---
# AES (Estándar de encriptación Avanzada)
- 1997
- NIST (National Institute of standards and Technology)
---
# AES
1. El algoritmo debe ser un sistema de cifrado de bloques simétrico.
2. Todo el diseño debe ser público.
3. Se deben soportar las longitudes de claves de 128, 192 y 256 bits.
4. Deben ser posibles las implementaciones tanto de software como de hardware.
5. El algoritmo debe ser público o con licencia en términos no discriminatorios.
---
# RJINDAL
- Cifrado simétrico por bloques (AES - 128)
## Estructura
1. **SubBytes** (Sustitución)
2. **ShiftRows** (Desplazamiento)
3. **MixColumns** (Mezcla)
4. **AddRoundKey** (XOR con clave de ronda):
---
# PROBLEMA DE LOS ALGORITMOS DE CLAVE SIMETRICA

---
#  - Electronic Code Book
# - Cipher Block Chaining
# - cipher feedback
# - Stream Cipher
# - Counter Mode
---
# EJEMPLO STREAM CIPHER
---

<img src="images/Pasted image 20250529180857.png" alt="" style="max-width: 80%; height: auto;">
---
# Clave Asimétrica
---
<img src="images/deepseek_mermaid_20250529_e8ff74.png" alt="" style="max-width: 80%; height: auto;">

---
