MAYA 2강 Object, Component
==========================
2018-11-09 정리
--------------

**Object and Component**
------------------------


![how to select Object and Component](image\6.png)


컴포넌트와 오브젝트의 차이점은 오브젝트는 한개의 오브젝트를 선택하는 반면 컴포넌트는 Face, Vertex, Edge등의 한개의 오브젝트를 나눠서 선택합니다.<br>
F8키를 통해서 컴포넌트와 오브젝트 모드를 바꿀 수 있다.


**Duplicate**
--------------


![Duplicate](image\7.png)


''Duplicate''는 한개 이상의 오브젝트를 2배로 늘려줍니다. 쉽게말해서 복사, 붙여넣기와 같은 기능이라 생각하면 됩니다.<br><br>
사용법

1.  Ctrl + D
2.  Edit > Duplicate
3.  Shift + Drag


**return**
----------

Ctrl + Z를 통해 작업을 되돌릴 수 있습니다.


1.**Edge Mode**
-------------


![Edge Mode](image\8.png)


Shift + DB Click을 통해 한 줄의 Edge를 선택할 수 있습니다. 이를 ''Edge loop''라고 합니다. F10키를 통해 Edge 모드에 진입할 수 있습니다.


2.**Vertex Mode**
---------------


![Vertex Mode](image\9.png)


Vertex는 꼭짓점을 선택해 점 하나하나를 이동시킬 수 있는 장점이 있습니다. F9키를 통해 Vertex 모드에 진입할 수 있습니다.


**Face Mode**
-------------


3.![Face Mode](image\10.png)


Face는 컴포넌트의 한 면을 선택해 이동시킬 수 있는 장점이 있습니다. F11키를 통해 Face 모드에 진입할 수 있습니다.<br>


![](image\11.png)

'W'키를 누른 상태로 마우스 클릭을 하면 이동기준을 바꿀 수 있는 여러 메뉴가나옵니다.<br>
ex) 월드 축 기준, Normal Average 기준 등등 주로 쓰이는 메뉴는 Object, World, Normal Average.

**Normal..?**
-> Face나 Vertex는 3d에서 고유한 방향을 가지고 있는데 그 방향이 ''Normal''이라는 개념이다.