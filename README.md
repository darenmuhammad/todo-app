# ***Method and Function***

## JSON.parse()

Digunakan untuk mengubah string JSON menjadi objek JavaScript asli.

### Contoh Penggunaan:

```javascript
const jsonStr = '{"name":"John", "age":30}';
const obj = JSON.parse(jsonStr);
console.log(obj.name); // Output: John
```

---

## localStorage

Digunakan untuk menyimpan data secara lokal di browser yang bertahan meski halaman di-refresh atau browser ditutup.

### Contoh Penggunaan:

```javascript
// Menyimpan Data
localStorage.setItem("key", "value");

// Mengambil Data
const value = localStorage.getItem("key");

// Menghapus Data
localStorage.removeItem("key");
```

---

## trim()

Menghapus spasi di awal dan akhir string.

### Contoh Penggunaan:

```javascript
const str = "  Hello World  ";
console.log(str.trim()); // Output: "Hello World"
```

---

## replace() + Regex

Mengganti bagian dari string. Jika digabungkan dengan regex, bisa digunakan untuk mengganti karakter tertentu.

### Contoh Penggunaan:

```javascript
const str = "Hello@World!";
const cleanStr = str.replace(/[^A-Za-z0-9\-\s]/g, '');
console.log(cleanStr); // Output: HelloWorld
```

---

## findIndex()

Menemukan index elemen pertama dalam array yang memenuhi kondisi tertentu.

### Contoh Penggunaan:

```javascript
const tasks = [{id: 1}, {id: 2}];
const index = tasks.findIndex(task => task.id === 2);
console.log(index); // Output: 1
```

---

## forEach()

Menjalankan sebuah fungsi pada setiap elemen array.

### Contoh Penggunaan:

```javascript
const numbers = [1, 2, 3];
numbers.forEach(num => console.log(num));
```

---

## addEventListener()

Menambahkan event listener ke elemen HTML untuk menangani interaksi user.

### Contoh Penggunaan:

```javascript
const button = document.getElementById("myBtn");
button.addEventListener("click", () => {
  alert("Button clicked!");
});
```

---

## close()

Menutup elemen dialog.

### Contoh Penggunaan:

```javascript
const dialog = document.getElementById("myDialog");
dialog.close();
```
