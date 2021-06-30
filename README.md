# iOS-Animations

<p align='center'>
  Table of Contents: Overview
<p align='center'>
</p>

## Section 1
| Animations with SwiftUI | Animation | 
| ------------- | ------------- | 
| [ Chapter 1: Introduction to Animations with SwiftUI ](https://github.com/egorskikh/IOS-Animations#introduction-to-animations-with-swiftui) | ![1](https://user-images.githubusercontent.com/60622982/116818663-401b8200-ab75-11eb-8225-ae41b5626494.gif)| 
| [ Chapter 2: Intermediate SwiftUI Animations ](https://github.com/egorskikh/IOS-Animations#intermediate-swiftui-animations) | ![3](https://user-images.githubusercontent.com/60622982/116818778-c3d56e80-ab75-11eb-870c-8f0a520e6d2e.gif) |

## Section 2
| View Animations  | Animation | 
| ------------- | ------------- | 
| [ Chapter 3: Getting Started with View Animations ](https://github.com/egorskikh/IOS-Animations#getting-started-with-view-animations) | ![гиф3](https://user-images.githubusercontent.com/60622982/116818340-95569400-ab73-11eb-8fee-a9ff0c85e073.gif) | 
| [ Chapter 4: Springs ](https://github.com/egorskikh/IOS-Animations#springs) | ![4](https://user-images.githubusercontent.com/60622982/116911011-0159fa80-ac4f-11eb-8166-56d6b71659b5.gif) |
| [ Chapter 5: Transitions](https://github.com/egorskikh/IOS-Animations#transitions) | ![5](https://user-images.githubusercontent.com/60622982/116919333-cad5ad00-ac59-11eb-9e0c-3bdf75fd26bf.gif) | 
| [ Chapter 6: View Animations in Practice ](https://github.com/egorskikh/IOS-Animations#view-animations-in-practice) | ![6](https://user-images.githubusercontent.com/60622982/117006994-c3fa7900-acf1-11eb-90d9-fc4230738009.gif) |
| [ Chapter 7: Keyframe Animations ](https://github.com/egorskikh/IOS-Animations#keyframe-animations) | ![7](https://user-images.githubusercontent.com/60622982/117275546-d0541280-ae66-11eb-90c3-b945b0f0e2b1.gif) | 

## Section 3
| Auto Layout | Animation | 
| ------------- | ------------- | 
| [ Chapter 8: Introduction to Auto Layout ](https://github.com/egorskikh/IOS-Animations#introduction-to-auto-layout) | - | 
| [ Chapter 9: Animating Constraints ](https://github.com/egorskikh/IOS-Animations#animating-constraints) | ![9](https://user-images.githubusercontent.com/60622982/117306842-b62b2c00-ae88-11eb-81cf-c1533e341527.gif) |

## Section 4
| Layer Animations  | Animation | 
| ------------- | ------------- | 
| [ Chapter 10: Getting Started with Layer Animations ](https://github.com/egorskikh/IOS-Animations#getting-started-with-layer-animations) | ![2021-06-30 15 17 36](https://user-images.githubusercontent.com/60622982/123959520-f0abd380-d9b6-11eb-8482-f5db3f13b680.gif) | 
| - | - |
| - | - | 
| - | - |
| - | - | 
| - | - |
| - | - | 
| - | - |

## Section 5
| View Controller Transition Animations | Animation | 
| ------------- | ------------- | 
| - | - | 
| - | - |
| - | - | 

## Section 6
| Animations with UIViewPropertyAnimator  | Animation | 
| ------------- | ------------- | 
| - | - | 
| - | - |
| - | - | 
| - | - |

## Section 7
| 3D Animations  | Animation | 
| ------------- | ------------- | 
| - | - | 
| - | - |


<p align='center'>
Table of Contents: Extended
<p align='center'>
</p>

## **Introduction to Animations with SwiftUI**
### Key points
- SwiftUI позволяет декларативно создавать пользовательский интерфейс и запрашивать анимацию любых изменений между «снимками» иерархии представлений.
- Вы добавляете анимацию с помощью модификатора .animation(_) в свои представления. В качестве параметра можно указать стандартную или настраиваемую анимацию.
- Вы анимируете различные модификаторы представления посредством изменения свойств состояния представления, которые запускают новый снимок и просят SwiftUI выполнить интерполяцию между предыдущим и текущим макетом.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/1.%20Animations%20with%20SwiftUI/1.%20Animations%20with%20SwiftUI/starter)
<br> </br>
## **Intermediate SwiftUI Animations**
### Key points
- Фигуры в SwiftUI придерживаются протокола просмотра, поэтому вы можете создавать интригующие анимации, включая преобразование, постепенное появление и исчезновение и морфинг фигур, точно так же, как вы делаете для любой другой анимации в своем пользовательском интерфейсе.
- Вы можете добавить больше состояний к вашим типам представлений, чтобы иметь возможность управлять более сложной, потенциально многоступенчатой ​​анимацией.
- Включение ввода с помощью жестов в состояние просмотра - это вопрос добавления нескольких дополнительных модификаторов к вашим представлениям, поэтому создание интерактивной анимации пользователя - это совсем несложно.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/1.%20Animations%20with%20SwiftUI/2.%20Intermediate%20SwiftUI%20Animations/starter)
<br> </br>

## **Getting Started with View Animations**
### Key points
- Вы создаете анимацию, используя один из вариантов UIView.animate (...).
- В закрытии анимации вы устанавливаете конечное состояние желаемой анимации, и UIKit автоматически создает плавную анимацию между текущим и конечным состояниями.
- Вы настраиваете свою анимацию, предоставляя значения UIView.AnimationOptions для установки свойств замедления, повторения и авторевертирования.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/2.%20View%20Animations/3.%20Getting%20Started%20with%20View%20Animations/starter)
<br> </br>
## **Springs**
### Key points
- Вы можете создавать визуальную обратную связь для взаимодействия с пользователем, создавая анимацию в ответ на действия пользователя.
- Вы создаете анимацию пружины аналогично «стандартной» анимации - дополнительными параметрами являются демпфирование пружины и начальная скорость.
- Комбинирование различных анимаций (с пружинами или без) создает богатые визуальные впечатления.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/2.%20View%20Animations/4.%20Springs/starter)
<br> </br>
## **Transitions**
### Key points
- Apple предоставляет набор предопределенных анимаций, называемых переходами, которые можно использовать для обработки особых изменений в состоянии пользовательского интерфейса вашего приложения.
- Переходы нацелены на добавление, удаление и замену представлений в иерархии представлений.
- При разработке анимации вы можете включить **Debug ▸ Toggle Slow Animations** в симуляторе, чтобы иметь возможность наблюдать за ними в замедленном движении.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/2.%20View%20Animations/5.%20Transitions/starter)
<br> </br>
## **View Animations in Practice**
### Key points
- Вы не ограничены анимацией отдельного свойства представления из одного вызова анимации; вы можете свободно комбинировать и перекрывать анимации.
- Для создания сложных эффектов вы можете использовать любые без исключения «трюки», которые, как вам кажется, требует текущая задача, включая создание временных представлений на время анимации.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/2.%20View%20Animations/6.%20View%20Animations%20in%20Practice/starter)
<br> </br>
## **Keyframe Animations**
### Key points
- Вы можете «связать» анимации, используя ключевые кадры, намного проще, чем использование завершения в стандартных API для создания последовательностей.
- Анимация по ключевым кадрам позволяет не только «связывать» анимации, но также «перекрывать» их и группировать их в целом любым удобным для вас способом.
- Не забывайте, что все значения синхронизации ключевых кадров относятся к полной анимации, тогда как API, определяющий полную последовательность, использует абсолютное время.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/2.%20View%20Animations/7.%20Keyframe%20Animations/starter)
<br> </br>

## **Introduction to Auto Layout**
### Key points
- С помощью Auto Layout вы не устанавливаете положение и размер ваших представлений в абсолютных значениях, а выражаете их относительно размера экрана или других представлений в иерархии представлений.
- Вы создаете новые ограничения между видами, перетаскивая их между ними, удерживая клавишу Ctrl, а затем выбирая тип ограничения во всплывающем меню.
- Как только для вида установлены ограничения (полностью определяющие его положение и размер), оно будет автоматически размещено на экране любого размера с помощью Auto Layout.
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/3.%20Auto%20Layout/8.%20Introduction%20to%20Auto%20Layout/starter)
<br> </br>
## **Animating Constraints**
### Key points
- [example](https://github.com/egorskikh/iOS-Animations/tree/main/3.%20Auto%20Layout/9.%20Animating%20Constraints/starter)
<br> </br>

## **Getting Started with Layer Animations**
### Key points
- Слоистая анимация дает вам больше возможностей, когда дело доходит до создания анимации пользовательского интерфейса. В отличие от анимации вида, вы можете анимировать множество дополнительных функций, таких как радиус угла, тень, ширину и цвет границы, стиль границы и многое другое.
- CABasicAnimation - это базовый класс модели анимации, который вы используете для описания желаемой анимации, которую вы передаете для визуализации, вызывая CALayer.add (_, forKey :).
- Поскольку анимация слоев - это модели данных, которые копируются Core Animation при добавлении к слою, вы можете повторно использовать один и тот же экземпляр модели для создания ряда похожих анимаций и даже настраивать некоторые из его свойств между добавлением его в разные слои.
- [example](https://github.com/egorskikh/IOS-Animations/blob/main/4.%20Layer%20Animations/10.%20Getting%20Started%20with%20Layer%20Animations/starter/BahamaAirLoginScreen/ViewController.swift)
<br> </br>
## **Animation Keys & Delegates**
### Key points
<br> </br>
## **Groups & Advanced Timing**
### Key points
<br> </br>
## **Layer Springs**
### Key points
<br> </br>
## **Layer Keyframe Animations & Struct Properties**
### Key points
<br> </br>
## **Shapes & Masks**
### Key points
<br> </br>
## **Gradient Animations**
### Key points
<br> </br>
## **Stroke & Path Animations**
### Key points
<br> </br>
## **Replicating Animations**
### Key points
<br> </br>
## **Presentation Controller & Orientation Animations**
### Key points
<br> </br>
## **UINavigationController Custom Transition Animations**
### Key points
<br> </br>
## **Interactive UINavigationController Transitions**
### Key points
<br> </br>
## **Getting Started with UIViewPropertyAnimator**
### Key points
<br> </br>
## **Intermediate Animations with UIViewPropertyAnimator**
### Key points
<br> </br>
## **Interactive Animations with UIViewPropertyAnimator**
### Key points
<br> </br>
## **UIViewPropertyAnimator View Controller Transitions**
### Key points
<br> </br>
## **Simple 3D Animations**
### Key points
<br> </br>
## **Intermediate 3D Animations**
### Key points
<br> </br>



















