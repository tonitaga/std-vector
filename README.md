# s21-vector by tonitaga
---

### Что это такое и с чем его едят?
`Vector — стандартный шаблон обобщённого программирования языка C++, реализующий динамический массив.`\
`Если сказать простыми словами: Vector — это замена стандартному динамическому массиву, память для которого выделяется вручную`

---
### Основная идея
`Бывают проекты, где запрещено использовать стандартные библиотечные контейнеры, данная реализация очень подойдет для использования в таких целях`

```c++
namespace s21 {
    template <typename T, typename Allocator = std::allocator<T>>
    class vector {

    };
}
```
---

### Как использовать?

`Используется также как и std::vector в этом отличий нет`

---
`© tonitaga 2022`
