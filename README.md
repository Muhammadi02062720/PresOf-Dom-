 > ## Windows
 ![](https://github.com/Muhammadi02062720/Pres-5-/blob/f801bdc3b60ed00ae9ba5b838e1c185d795c32b5/images/Rectangle%208.png)

> ## What is Dom in javascript ?
 >The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page

 ![](https://github.com/Muhammadi02062720/Pres-5-/blob/334eed3e1f1e2cf77a03d5f002817106b3d50ccd/images/Screenshot_6.png)

 > ##### There are two basic methods in js :

 1. querySelector() method.
 2. querySelectorAll() method 

 ![](/Screenshot_6.png)

 > 1. The Document method querySelector() returns the first Element within the document that matches the specified selector, or group of selectors. If no matches are found, null is returned.

2. The Document method querySelectorAll() returns a static (not live) NodeList representing a list of the document's elements that match the specified group of selectors.

 > ## What is innerHTML method ?

  >Свойство элемента innerHTML получает или задает разметку HTML или XML, содержащуюся внутри элемента.

  ![](/Screenshot_1.png)

> ## Html events …

 >События HTML — это специальные глобальные атрибуты, используемые в тегах для вызова обработчиков событий, написанных на различных языках сценариев таких, как JavaScript и вызываемых, когда на странице происходит какое-либо действие. События позволяют сделать вашу страницу динамической.
![](/Screenshot_2.png)

> #### creatElement() 
>The JavaScript document.createElement() method allows you to create and return a 
    new element (an empty Element node) with the specified tag name.

  1. createElement(elementName): Creates an html element whose tag is
     passed as a parameter. Returns the created element

  В HTML-документе метод document.createElement() создает HTML-элемент, указанный tagName, или HTMLUnknownElement, если tagName не распознан.
![](https://github.com/Muhammadi02062720/Pres-5-/blob/1c8ecf0656bbdb134de7ef494a7518786a95a2e8/images/Screenshot_10.png)

> ## HTML DOM Element appendChild()

 >Метод appendChild() добавляет узел (элемент) в качестве последнего
дочернего элемента элемента.
appendChild() добавляет узел в конец списка дочерних элементов
указанного родительского узла. Если данный дочерний элемент является ссылкой на
существующий узел в документе, то appendChild() 
функция перемещает его из текущего положения в новое положение
![](/Screenshot_3.png)

>  #### classlist

 >Свойство classList возвращает псевдомассив DOMTokenList, содержащий все классы элемента.

   >ClassList является геттером. Возвращаемый им объект имеет несколько методов:
   >1. add( String [,String] )
     >Добавляет элементу указанные классы
     ![](/Screenshot_4.png)

   >2. remove( String [,String] ) 
     >Удаляет у элемента указанные классы item ( Number ) Результат аналогичен вызову сlassList[Number]
       ![](/Screenshot_5.png)

   >3. toggle ( String [, Boolean]) 
     >Если класс у элемента отсутствует - добавляет, иначе - убирает. Когда вторым параметром передано false - удаляет указанный класс, а если true - добавляет. Если вторым параметром передан undefined или переменная с typeof == 'undefined', поведение будет аналогичным передаче только первого параметра при вызове toggle. contains ( String ) Проверяет, есть ли данный класс у элемента (вернёт true или false)
     ![](/Screenshot_7.png)
   