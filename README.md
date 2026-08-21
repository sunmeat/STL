# C++ STL & Advanced Data Structures

Репозиторій містить навчальні матеріали, приклади використання Standard Template Library (STL) у C++, а також власні реалізації базових і просунутих структур даних та алгоритмів.

---

## 📚 Основні Розділи та Теми

### 1. Standard Template Library (STL)
- **Контейнери:**
  - Послідовні (`std::vector`, `std::list`, `std::deque`, `std::array`).
  - Асоціативні (`std::map`, `std::set`, `std::multimap`, `std::multiset`).
  - Неупорядковані асоціативні (`std::unordered_map`, `std::unordered_set`).
- **Адаптери:** `std::stack`, `std::queue`, `std::priority_queue`.
- **Алгоритми (`<algorithm>`):** Сортування, пошук, трансформація, фільтрація, використання лямбда-виразів.
- **Ітератори:** `input`, `output`, `forward`, `bidirectional`, `random_access`.

### 2. Кастомні Структури Даних
- Реалізація шаблонів однозв'язного та двозв'язного списків.
- Бінарне дерево пошуку (BST).
- Кастомні динамічні масиви та стеки/черги.

---

## 🛠 Вимоги та Компіляція

Для роботи з проектом необхідний компілятор з підтримкою **C++17** або новішої версії.

### Запуск через Command Line (GCC/Clang)

```bash
# Клонування репозиторію
git clone https://github.com/sunmeat/STL.git
cd STL

# Компіляція прикладу
g++ -std=c++17 -Wall main.cpp -o stl_demo

# Запуск
./stl_demo
```

---

## 🚀 Приклади Коду

### Робота з STL Контейнерами та Алгоритмами

```cpp
#include <iostream>
#include <vector>
#include <algorithm>

int main() {
    std::vector<int> numbers = {5, 2, 8, 1, 9};

    // Сортування за допомогою std::sort
    std::sort(numbers.begin(), numbers.end());

    // Вивід елементів
    for (int n : numbers) {
        std::cout << n << " ";
    }
    std::cout << std::endl;

    return 0;
}
```

---

## 👤 Автор

* **GitHub:** [@sunmeat](https://github.com/sunmeat)
* **Підтримка:** [Monobank](https://send.monobank.ua/2YRyvEGWAn)
