from pathlib import Path

# Contenido del archivo README.md adaptado para VÉRTICE MAGAZINE
readme_content = """# VÉRTICE MAGAZINE ✧

Bienvenidxs a VÉRTICE — una revista de moda, estilismo y producción visual con base en Rosario, Argentina.  
Nos dedicamos a contar historias con estética, mirada crítica y profundidad cultural.

Cada edición es un universo: imágenes que inspiran, textos que incomodan, entrevistas que importan.

🖤 Biblioteca digital de ediciones independientes  
📸 Producción fotográfica y audiovisual  
🧵 Diseño, dirección de arte y estilismo  
🌎 Una mirada contemporánea sobre lo que vestimos y lo que somos

## 📚 Explorá nuestras ediciones  
👉 [Ver ediciones digitales](https://verticemagazine.github.io)

## 🔗 También podés encontrarnos en  
- [Instagram](https://instagram.com/verticemagazine)  
- [Pinterest](https://pinterest.com/verticemagazine)  
- [Substack](https://verticemagazine.substack.com)

---

> VÉRTICE es una esquina donde se cruzan la moda, la cultura y lo independiente.  
> Nos animamos a mirar desde otro ángulo.
"""

# Guardar el archivo
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content, encoding="utf-8")

readme_path.name
