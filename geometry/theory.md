# Геометрия

![](https://mypresentation.ru/documents_6/fb868cd25bc1dce2f8dbefb4533fac8f/img9.jpg)

Следовательно, ножество точек прямой, проходящей через две точки с координатами (x1; y1) и (x2; y2), удовлетворяет уравнению

(x – x1) * (y2 – y1) – (y – y1) * (x2 – x1) = 0.

Как записать точку и вектор:

```cpp
struct Point{
    int x;
    int y;
};
struct Vector{
    int x;
    int y;
};

double len_vect(Vector a, Vector b){
    double res = sqrt(pow((b.x-a.x),2) + pow((b.y-a.y),2));
    return res;
}
int main(){
    Vector pt1,pt2;
    cin>> pt1.x >> pt1.y >> pt2.x >> pt2.y;
    cout<<len_vect(pt1,pt2);
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

