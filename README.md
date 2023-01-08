[![Build status](https://ci.appveyor.com/api/projects/status/1wdjnel0kqqgjfk8?svg=true)](https://ci.appveyor.com/project/Serg1811/ajs-11-3)

## Генераторы (задача со звёздочкой)

**Важно**: данная задача не является обязательной 

### Легенда

Как вы знаете, объекты, позволяющие организовать итерирование, содержат метод с "именем" `Symbol.iterator`. Напишите функцию `canIterate`, которая определяет, соответствует ли объект протоколу итерирования, возвращая, соответственно, `true`/`false`.

Примеры использования:
```javascript
canIterate(new Map()); // true
canIterate(new Set()); // true
canIterate(null); // false
canIterate(10); // false
canIterate("Netology"); // true
```