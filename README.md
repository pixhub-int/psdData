# psdInfo

```json
{
	"width": {num}, // ширина документа
	"height": {num}, // высота документа
	"image": {array}, // изображение документа

	// слои
	"layers": [
		{
			// положение
			"top": {num},
			"right": {num},
			"bottom": {num},
			"left": {num},

			// размеры
			"width": {num},
			"height": {num},

			// текстовые данные
			"text": {
				"data": {string}, // содержимое
				"sizes": {array}, // размеры
				"fonts": {array}, // шрифты
				"line-height": {num}, // высота строки
				"color": {string} // цвет текста
			},

			// эффекты
			"effects": {
				"colorOverlay": {obj}
			},

			"name": {string}, // имя
			"id": {num}, // идентификатор
			"opacity": {num}, // общая прозрачность
			"visibility": {bool}, // видимость слоя
			"image": {array} // изображение слоя
		}
	]
}
```
