# Геометрия

![](https://mypresentation.ru/documents_6/fb868cd25bc1dce2f8dbefb4533fac8f/img9.jpg)

Следовательно, ножество точек прямой, проходящей через две точки с координатами (x1; y1) и (x2; y2), удовлетворяет уравнению

(x – x1) * (y2 – y1) – (y – y1) * (x2 – x1) = 0.

Как записать точку и вектор:

```cpp
struct point{
    long long x;
    long long y;
};

struct c_vector{
    long long x;
    long long y;
};

point new_vec (point p,c_vector v){
    point end_of = {p.x+v.x,p.y+v.y};
    return end_of;
}
```
## Длина отрезка и координаты вектора
![](https://fsd.multiurok.ru/html/2017/03/01/s_58b6cf6391947/img2.jpg)

## Скалярное произведение векторов
![](https://prezentacii.org/upload/cloud/19/09/162649/images/screen10.jpg)

## Псевдоскалярное произведение векторов
![](https://cf.ppt-online.org/files/slide/m/mxrE967SfRy2nXkFgb4qBG0lwzQUAcoeM1ZtDL/slide-2.jpg)

## Условия существования треугольника
![](https://cf2.ppt-online.org/files2/slide/r/RMhxcTUL74sfAupFmiyB5YOkeD2XjqNPbwa3nH/slide-2.jpg)

