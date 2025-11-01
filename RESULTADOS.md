# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 7 correctas de 41 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, UPPER(SUBSTRING(nombre,1,2)) AS iniciales FROM fabricante' at line 2


## ❌ Query 9: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, ROUND(precio,1) as precio FROM producto' at line 2


## ❌ Query 10: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, ROUND(precio,0) as precio_truncado FROM producto ORDER BY' at line 2


## ❌ Query 11: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT codigo_fabricante FROM producto ORDER BY codigo_fabricante ASC' at line 2


## ❌ Query 12: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT DISTINCT codigo_fabricante FROM producto ORDER BY codigo_fabricant' at line 2


## ❌ Query 13: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre FROM fabricante ORDER BY nombre ASC' at line 2


## ❌ Query 14: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre FROM fabricante ORDER BY nombre DESC' at line 2


## ❌ Query 15: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, precio FROM producto ORDER BY nombre ASC, precio DESC' at line 2


## ❌ Query 16: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT * FROM fabricante LIMIT 5' at line 2


## ❌ Query 17: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT * FROM fabricante LIMIT 2 OFFSET 3' at line 2


## ❌ Query 18: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, precio FROM producto ORDER BY precio ASC LIMIT 1' at line 2


## ❌ Query 19: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, precio FROM producto ORDER BY precio DESC LIMIT 1' at line 2


## ❌ Query 20: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre FROM producto WHERE codigo_fabricante='2'' at line 2


## ❌ Query 21: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as nombre_del_fa' at line 2


## ❌ Query 22: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as nombre_del_fa' at line 2


## ❌ Query 23: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.codigo, producto.nombre, fabricante.codigo AS codigo_fabric' at line 2


## ❌ Query 24: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante F' at line 2


## ❌ Query 25: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante F' at line 2


## ❌ Query 26: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre FROM producto J' at line 2


## ❌ Query 27: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre FROM producto J' at line 2


## ❌ Query 28: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre AS fabricante F' at line 2


## ❌ Query 29: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante FRO' at line 2


## ❌ Query 30: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante FRO' at line 2


## ❌ Query 31: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante FRO' at line 2


## ❌ Query 32: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT producto.nombre, producto.precio, fabricante.nombre as fabricante FRO' at line 2


## ❌ Query 33: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT DISTINCT fabricante.codigo, fabricante.nombre as fabricante FROM fab' at line 2


## ❌ Query 34: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT fabricante.nombre AS fabricante, producto.nombre AS producto FROMÂ' at line 2


## ❌ Query 35: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT fabricante.nombre AS fabricante FROM fabricante LEFT JOIN product' at line 2


## ❌ Query 36: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, precio FROM producto WHERE codigo_fabricante = ( SELECTÂ' at line 2


## ❌ Query 37: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT * FROM producto WHERE precio = ( SELECT MAX(precio) FROM produ' at line 2


## ❌ Query 38: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre FROM producto WHERE codigo_fabricante = ( SELECT codigo ' at line 2


## ❌ Query 39: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre FROM producto WHERE codigo_fabricante = ( SELECT codigo ' at line 2


## ❌ Query 40: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT * FROM producto WHERE precio >= ( SELECT MAX(precio) FROM prod' at line 2


## ❌ Query 41: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT nombre, precio FROM producto WHERE codigo_fabricante = ( SELECTÂ' at line 2

