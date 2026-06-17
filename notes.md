# 🎨 Tailwind CSS Basic Notes

## 1. Adding Tailwind CSS

```html
<script src="https://cdn.tailwindcss.com"></script>
```

---

# 2. Text Classes

| Class         | Meaning     |
| ------------- | ----------- |
| text-center   | Center text |
| text-left     | Left align  |
| text-red-500  | Red color   |
| text-blue-500 | Blue color  |
| text-white    | White color |
| text-2xl      | Large text  |
| font-bold     | Bold text   |

### Example

```html
<h1 class="text-3xl font-bold text-blue-500 text-center">
    Hello Tailwind
</h1>
```

---

# 3. Background Colors

| Class        | Meaning          |
| ------------ | ---------------- |
| bg-red-500   | Red background   |
| bg-blue-500  | Blue background  |
| bg-green-500 | Green background |

### Example

```html
<div class="bg-blue-500 text-white">
    Welcome
</div>
```

---

# 4. Padding

| Class | Meaning              |
| ----- | -------------------- |
| p-2   | Small padding        |
| p-4   | Medium padding       |
| px-4  | Left & Right padding |
| py-2  | Top & Bottom padding |

### Example

```html
<div class="bg-gray-200 p-4">
    Content
</div>
```

---

# 5. Margin

| Class | Meaning          |
| ----- | ---------------- |
| m-4   | Margin all sides |
| mt-4  | Top margin       |
| mb-4  | Bottom margin    |

### Example

```html
<div class="mt-4">
    Hello
</div>
```

---

# 6. Width and Height

| Class    | Meaning            |
| -------- | ------------------ |
| w-full   | Full width         |
| w-1/2    | 50% width          |
| h-screen | Full screen height |

### Example

```html
<div class="w-full h-20 bg-green-500"></div>
```

---

# 7. Border and Radius

| Class      | Meaning         |
| ---------- | --------------- |
| border     | Add border      |
| border-2   | 2px border      |
| rounded    | Rounded corners |
| rounded-lg | Large radius    |

### Example

```html
<div class="border rounded-lg p-4">
    Box
</div>
```

---

# 8. Flexbox

| Class          | Meaning             |
| -------------- | ------------------- |
| flex           | Enable flexbox      |
| justify-center | Horizontal center   |
| items-center   | Vertical center     |
| gap-4          | Space between items |
| flex-col       | Column layout       |

### Example

```html
<div class="flex justify-center gap-4">
    <div>Box1</div>
    <div>Box2</div>
</div>
```

---

# 9. Grid

| Class       | Meaning           |
| ----------- | ----------------- |
| grid        | Enable grid       |
| grid-cols-2 | Two columns       |
| grid-cols-3 | Three columns     |
| gap-4       | Gap between items |

### Example

```html
<div class="grid grid-cols-3 gap-4">
    <div>1</div>
    <div>2</div>
    <div>3</div>
</div>
```

---

# 10. Buttons

### Example

```html
<button class="bg-blue-500 text-white px-4 py-2 rounded">
    Click Me
</button>
```

---

# 11. Hover Effect

### Example

```html
<button class="bg-green-500 hover:bg-green-700 text-white p-2">
    Submit
</button>
```

---

# 12. Shadow

| Class     | Meaning       |
| --------- | ------------- |
| shadow    | Small shadow  |
| shadow-md | Medium shadow |
| shadow-lg | Large shadow  |

### Example

```html
<div class="shadow-lg p-4">
    Card
</div>
```

---

# 13. Responsive Design

| Prefix | Screen Size |
| ------ | ----------- |
| sm:    | ≥ 640px     |
| md:    | ≥ 768px     |
| lg:    | ≥ 1024px    |

### Example

```html
<div class="bg-red-500 md:bg-blue-500">
    Responsive Box
</div>
```

Mobile → Red

Tablet/Desktop → Blue

---

# 14. Position

| Class    | Meaning           |
| -------- | ----------------- |
| relative | Relative position |
| absolute | Absolute position |
| fixed    | Fixed position    |
| sticky   | Sticky position   |

---

# 15. Display Classes

| Class  | Meaning        |
| ------ | -------------- |
| block  | Block element  |
| inline | Inline element |
| hidden | Hide element   |
| flex   | Flexbox        |
| grid   | Grid layout    |

---

# ⭐ Most Frequently Used Classes

```html
text-center
font-bold
bg-blue-500
text-white
p-4
m-4
rounded-lg
shadow-lg
flex
justify-center
items-center
grid
gap-4
hover:bg-blue-700
w-full
h-screen
border
```

# 🚀 Tailwind CSS Roadmap

### Basics

✔ Colors
✔ Typography
✔ Margin & Padding
✔ Width & Height
✔ Borders

### Layout

✔ Flexbox
✔ Grid
✔ Positioning

### Components

✔ Buttons
✔ Cards
✔ Navbar
✔ Forms

### Advanced

✔ Responsive Design
✔ Hover Effects
✔ Transitions
✔ Animations
