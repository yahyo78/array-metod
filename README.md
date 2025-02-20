# array-metod

# Методҳои массив дар JavaScript

## 1. **Илова ва ҳазфи элементҳо**

- `push(element)`: **Иловаи элемент ба охири массив**
  ```js
  let arr = [1, 2, 3];
  arr.push(4);
  console.log(arr); // [1, 2, 3, 4]
  ```
  
- `pop()`: **Ҳазфи охирин элемент аз массив**
  ```js
  let arr = [1, 2, 3];
  arr.pop();
  console.log(arr); // [1, 2]
  ```

- `unshift(element)`: **Иловаи элемент ба аввали массив**
  ```js
  let arr = [2, 3];
  arr.unshift(1);
  console.log(arr); // [1, 2, 3]
  ```

- `shift()`: **Ҳазфи элементи аввал аз массив**
  ```js
  let arr = [1, 2, 3];
  arr.shift();
  console.log(arr); // [2, 3]
  ```

## 2. **Табдил додани массив**

- `join(separator)`: **Табдили массив ба сатри матнӣ бо ҷудокунанда**
  ```js
  let arr = ["apple", "banana", "cherry"];
  console.log(arr.join(" - ")); // "apple - banana - cherry"
  ```

- `splice(start, deleteCount, ...items)`: **Илова, ҳазф ё иваз кардани элементҳо**
  ```js
  let arr = [1, 2, 3, 4];
  arr.splice(1, 2, 9, 10);
  console.log(arr); // [1, 9, 10, 4]
  ```

## 3. **Оператсияҳо бо массив**

- `concat(array)`: **Якҷо кардани массивҳо**
  ```js
  let arr1 = [1, 2];
  let arr2 = [3, 4];
  let result = arr1.concat(arr2);
  console.log(result); // [1, 2, 3, 4]
  ```

- `toString()`: **Табдили массив ба сатри матнӣ**
  ```js
  let arr = [1, 2, 3];
  console.log(arr.toString()); // "1,2,3"
  ```

- `slice(start, end)`: **Гирифтани порчаи массив**
  ```js
  let arr = [1, 2, 3, 4, 5];
  console.log(arr.slice(1, 4)); // [2, 3, 4]
  ```

- `toReversed()`: **Гузоштани элементҳо ба тартиби баръакс** (Методи нав дар ES2023)
  ```js
  let arr = [1, 2, 3];
  console.log(arr.toReversed()); // [3, 2, 1]
  ```

  ![Намунаи тасвир](https://avatars.mds.yandex.net/i?id=c7df27cd394f675958c852aa63ffa2d0_l-5156037-images-thumbs&n=13)
