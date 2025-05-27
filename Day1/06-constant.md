
### 🧱 Constant

> 💡 **Syntax** => `define("CONSTANT_NAME", value);`  
> Constants are like variables... but they never change! 🚫🌀  
> Once defined, you can't reassign them. They're **locked and loaded** 🔐

---

```php
<?php

// ✅ Valid constant names
define("ONE", "first thing");
define("__Two__", "second value");

// ❌ Invalid constant name (can't start with a number)
define("2TWO", "test"); // This will cause a warning ⚠️

/*
You already know how to echo, right? 😉
Let's cheat a bit:
*/
echo ONE . "\n";
echo __Two__ . "\n";

// echo 2TWO; ❌ Nope! Invalid name, remember?
?>
````

---

### 📘 Notes:

- Constant names **should not** start with numbers ❌
    
- No need for `$` when using constants (they're not variables!) 🧠
    
- They are **global by default**, accessible anywhere in your code 🌍