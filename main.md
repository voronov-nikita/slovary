# Типо формулы

$$
\int{\frac{dx}{a^2+x^2}=\frac{1}{a}\arctan\frac{x}{a}+C  (a\neq0)}
$$

$$
\int{\frac{dx}{\sqrt{a^2\pm x^2}}}=\ln|{x+\sqrt{x^2\pm a^2}| + C}(a>0)
$$

# **Словари в Python**

![Картинка1](/img/pythonis.webp)

## Что такое *словарь*

*Словари в Python* - неупорядоченные коллекции произвольных объектов с доступом по ключу. Их иногда ещё называют ассоциативными массивами или хеш-таблицами.

![Картинка2](/img/images.png)

```python
d = {"first": 1, "second":2, "third":3}
a = {"first": 1, "second":2, "third":3}
b = {"first": 1, "second":2, "third":3}
```

## Отличие от массивов

В массивах, в отличае от словарей, к эллементам обращаются по их индексу. А к словарям, по их ключу.

```python
ls = [1, 2, 3]
di = {"first": 1, "second":2, "third":3}

print(ls[0])
print(di["first"])
```

## Методы словарей

- `dict.clear()` - очищает словарь

- `dict.copy()` - копирует словарь

- `dict.items()` - возвращает пары (ключ, значение)

- `dict.keys()` - возвращает ключи в словаре

Больше команд можно взять [здесь](https://pythonworld.ru/tipy-dannyx-v-python/slovari-dict-funkcii-i-metody-slovarej.html).

## Примеры использования

```python
#Словарь значений электронных почт
emails = {'mgu.edu': ['andrei_serov', 'alexander_pushkin', 'elena_belova', 'kirill_stepanov'],
       'gmail.com': ['alena.semyonova', 'ivan.polekhin', 'marina_abrabova'],
       'msu.edu': ['sergei.zharkov', 'julia_lyubimova', 'vitaliy.smirnoff'],
       'yandex.ru': ['ekaterina_ivanova', 'glebova_nastya'],
       'harvard.edu': ['john.doe', 'mark.zuckerberg', 'helen_hunt'],
       'mail.ru': ['roman.kolosov', 'ilya_gromov', 'masha.yashkina']}
```

## Задачи на этот урок

- [x] Изучить словари
- [ ] Попробовать создать словарь
- [x] Определить возможность использования словарей в реальной жизни
- [xS] Решить задачи
