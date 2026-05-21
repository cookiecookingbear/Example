# Study Note
1. C#
    1. 변수
    1. 자료형
    1. 자료구조
        - Array
            > Array(어레이, 배열)은 arr[]의 형식으로 사용한다.
             컨테이너의 길이가 고정되어 있고, 편의기능이 없다.
             대신 단순한 만큼 자원소모가 적다.
        - List
            > List(리스트)는 List\<T>의 형식으로 사용한다.\
             컨테이너의 길이가 가변적이고 Add, Remove, Find, Sort등의 편의기능이 있지만,Array보다는 자원소모가 많다.\
             using System.Collections.Generic; 
             네임스페이스를 사용해야 한다.
            
    1. 크기와 범위
1. Unity
    - Editor
        - Transform
    - 3D Grapics
1. Mathmatics
    - Vector
        - Position
        - Direction
        - Dot Product



# 도움말
- 이미지 넣는 법
    - 외부 이미지
    > ![유니티 로고.](data:image/png;base64,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)\
    > 위처럼 ![이미지 설명](이미지 주소)의 형식으로 작성한다.
    - 내부 이미지
     >![언리얼 로고](image/언리얼%20로고.png)\
     >위처럼 ![이미지 설명](상대 경로)의 형식으로 작성한다.
     >사실 상대경로 작성 안하고 탐색기에서 드래그해서 넣었음.