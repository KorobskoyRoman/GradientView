# GradientView
Позволяет установить градиент на любой UIView() с указанием цветов и направления.

## Как использовать:

Указываем наш градиент:

 let gradientView = GradientView(from: .topTrailing, to: .bottomLeading, startColor: #colorLiteral(red: 0.4745098054, green: 0.8392156959, blue: 0.9764705896, alpha: 1), endColor: #colorLiteral(red: 0.9098039269, green: 0.4784313738, blue: 0.6431372762, alpha: 1))
 
 В параметры подставляем откуда будет "течь" наш градиент и куда (например, из право верх в нижний левый угол).
