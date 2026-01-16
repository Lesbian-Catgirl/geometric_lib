# Library description
Geometric Lib is a library for calculating areas and perimeters of different geometric figures: circle, rectangle, square.

---

# Fugires
## [Circle](../circle.py)
### Paremeters
    - r: radius of the circle
### Functions
  - `area(r)`: Returns area of the circle

    **Example:**
    ```python
    from circle import area
    print(area(5))  # Output: 78.5398 (assuming π=3.14159)
    ```
  - `perimeter(r)`: Returns perimeter of the circle
    
    **Example:**
    ```python
    from circle import perimeter
    print(perimeter(5))  # Output: 31.4159 (assuming π=3.14159)
    ```
---

  ## [Rectangle](../rectangle.py)

### Parameters
- a: length of one side of the rectangle
- b: length of other side of the rectangle 
### Functions
  - `area(a, b)`: Returns area of the rectangle
    
    **Example:**
    ```python
    from rectangle import area
    print(area(3, 6))  # Output: 18
    ```
  - `perimeter(a, b)`: Returns perimeter of the rectangle 
    
    **Example:**
    ```python
    from rectangle import perimeter
    print(perimeter(6, 3))  # Output: 18
    ```
---

## [Square](../square.py)

### Parameters
    - int a: length of the square side  
### Functions

  - `area(a)`: Returns area of the square
    
    **Example:**
    ```python
    from square import area
    print(area(2))  # Output: 4
    ```
  - `perimeter(a)`: Returns perimeter of the square
    
    **Example:**
    ```python
    from square import perimeter
    print(perimeter(3))  # Output: 12
    ```
---
## [Triangle](../triangle.py)

### Parameters
    - int a: length of the first side of the triangle
    - int b: length of the second side of the triangle
    - int c: length of the third side of the triangle
    - int h: triangle height
### Functions

  - `area(a, h)`: Returns area of the triangle
    
    **Example:**
    ```python
    from triangle import area
    print(area(2, 4))  # Output: 2
    ```
  - `perimeter(a, b, c)`: Returns perimeter of the triangle
    
    **Example:**
    ```python
    from square import perimeter
    print(perimeter(3, 12, 6))  # Output: 21
    ```

# History of commits

- [commit 98837170a888cae5d986b329141a6e7676797dd6](https://github.com/Lesbian-Catgirl/geometric_lib/commit/98837170a888cae5d986b329141a6e7676797dd6)\
Author: Viktor Shubin <115558481+Lesbian-Catgirl@users.noreply.github.com>\
Date:   Thu Sep 18 01:20:17 2025 +0300

    Descriptions in circle.py
    Added descriptions for circle functions

- [commit 87338f834ee5c09897f201e3c9bc2285f5fe499c](https://github.com/Lesbian-Catgirl/geometric_lib/commit/87338f834ee5c09897f201e3c9bc2285f5fe499c)\
Author: Viktor Shubin <115558481+Lesbian-Catgirl@users.noreply.github.com>\
Date:   Thu Sep 18 01:18:28 2025 +0300

    Description in rectangle.py
    Added descriptions for rectangle functions

- [commit 310bbc67dc9b585e05546357ab30f4618017f380](https://github.com/Lesbian-Catgirl/geometric_lib/commit/310bbc67dc9b585e05546357ab30f4618017f380)\
Author: Viktor Shubin <115558481+Lesbian-Catgirl@users.noreply.github.com>\
Date:   Thu Sep 18 01:14:37 2025 +0300

    Fix in square.py
    Fixed commentary chars
    \``` -> '''

- [commit d4b5762abd9a6073f7b1729cf6d76992381180da](https://github.com/Lesbian-Catgirl/geometric_lib/commit/d4b5762abd9a6073f7b1729cf6d76992381180da)\
Author: Viktor Shubin <115558481+Lesbian-Catgirl@users.noreply.github.com>\
Date:   Thu Sep 18 01:12:39 2025 +0300

    Descriprion to square.py
    Added descriptions to functions for square


- [commit f1225e123809ff78dd0136e3843c96bb5291d842](https://github.com/Lesbian-Catgirl/geometric_lib/commit/f1225e123809ff78dd0136e3843c96bb5291d842)\
Author: Longren <lon.g.ren@yandex.ru>\
Date:   Wed Sep 17 23:47:36 2025 +0300

    Fixed mistake in rectangle.py:
    changed perimeter function

- [commit 75f5a86929f44ae40513a255296860f3eade9f4b](https://github.com/Lesbian-Catgirl/geometric_lib/commit/75f5a86929f44ae40513a255296860f3eade9f4b)\
Author: Longren <lon.g.ren@yandex.ru>\
Date:   Wed Sep 17 23:42:22 2025 +0300

    Added new file:    rectangle.py

- [commit d078c8d9ee6155f3cb0e577d28d337b791de28e2](https://github.com/Lesbian-Catgirl/geometric_lib/commit/d078c8d9ee6155f3cb0e577d28d337b791de28e2)\
Author: smartiqa <info@smartiqa.ru>\
Date:   Thu Mar 4 14:55:29 2021 +0300

    L-03: Docs added

- [commit 8ba9aeb3cea847b63a91ac378a2a6db758682460](https://github.com/Lesbian-Catgirl/geometric_lib/commit/8ba9aeb3cea847b63a91ac378a2a6db758682460)\
Author: smartiqa <info@smartiqa.ru>\
Date:   Thu Mar 4 14:54:08 2021 +0300

    L-03: Circle and square added
