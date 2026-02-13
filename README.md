
 
![Example](docs/radius-8.png)


> *A dynamic, live-updating calendar widget for GitHub profiles.* 

---
</div>


**Calendar-by-Cygra** was built to bridge that gap. This project provides a lightweight, high-performance API that serves a dynamic image file reflecting the exact date of the current day. No more manual edits, no more outdated info—just a clean, automated badge that proves you are here, active, and building in real-time. ⚡




```url
![](https://profile-calendar.vercel.app/image?font=juicy-fills&bgColor=pink&radius=8)
```

# Apply on your profile


<div align="center">
  
| | |
| :---: | :---: |
| <details><summary><img src="https://profile-calendar.vercel.app/image?title=DASHBOARD&font=cheese-orange&fontSize=80&bgColor=%23F8FAFC&textColor=%230F172A&radius=15" width="440"></summary>`title=DASHBOARD`<br>`bgColor=%23F8FAFC`<br>`textColor=%230F172A`</details> | <details><summary><img src="https://profile-calendar.vercel.app/image?title=CREATIVE&font=cheese-orange&fontSize=80&bgColor=%23EEF2FF&textColor=%23312E81&radius=15" width="440"></summary>`title=CREATIVE`<br>`bgColor=%23EEF2FF`<br>`textColor=%23312E81`</details> |
| <details><summary><img src="https://profile-calendar.vercel.app/image?title=PREMIUM&font=cheese-orange&fontSize=80&bgColor=%23FFF7ED&textColor=%239A3412&radius=15" width="440"></summary>`title=PREMIUM`<br>`bgColor=%23FFF7ED`<br>`textColor=%239A3412`</details> | <details><summary><img src="https://profile-calendar.vercel.app/image?title=NEON+PULSE&font=cheese-orange&fontSize=80&bgColor=%23F5F3FF&textColor=%235B21B6&radius=15" width="440"></summary>`title=NEON+PULSE`<br>`bgColor=%23F5F3FF`<br>`textColor=%235B21B6`</details> |
| <details><summary><img src="https://profile-calendar.vercel.app/image?title=DARK+MODE&font=cheese-orange&fontSize=80&bgColor=%23F1F5F9&textColor=%230F172A&radius=15" width="440"></summary>`title=DARK_MODE`<br>`bgColor=%23F1F5F9`<br>`textColor=%230F172A`</details> | <details><summary><img src="https://profile-calendar.vercel.app/image?title=SOFT+ICE&font=cheese-orange&fontSize=80&bgColor=%23ECFEFF&textColor=%23015559&radius=15" width="440"></summary>`title=SOFT_ICE`<br>`bgColor=%23ECFEFF`<br>`textColor=%23015559`</details> |
| <details><summary><img src="https://profile-calendar.vercel.app/image?title=VIBRANT&font=cheese-orange&fontSize=80&bgColor=%23FFF1F2&textColor=%239F1239&radius=15" width="440"></summary>`title=VIBRANT`<br>`bgColor=%23FFF1F2`<br>`textColor=%239F1239`</details> | <details><summary><img src="https://profile-calendar.vercel.app/image?title=AURORA&font=cheese-orange&fontSize=80&bgColor=%23F0FDF4&textColor=%23065F46&radius=15" width="440"></summary>`title=AURORA`<br>`bgColor=%23F0FDF4`<br>`textColor=%23065F46`</details> |

</div>

## ⚙️ Parameters

Customize your calendar widget by passing query parameters in the URL.

```url
![](https://profile-calendar.vercel.app/image?font=juicy-fills&bgColor=pink&radius=8)
```

<div align="center">

  
| ✨ Parameter | 📦 Type | 🧩 Description | 🎯 Default |
|-------------|:------:|---------------|:----------:|
| `width`     | number | Width of the generated image (in pixels). | `1200` |
| `height`    | number | Height of the generated image (in pixels). | `100` |
| `textColor` | string | Text color (hex). Use `%23` instead of `#`.<br>Example: `%23ffffff` | `#000000` |
| `bgColor`   | string | Background color (hex or `transparent`).<br>Example: `%23000000` | `#ffffff` |
| `fontSize`  | number | Font size of the text (in pixels). | `60` |
| `font`      | string | Font family for the text.<br>See → [Available Fonts](#fonts) | `cheese-orange` |
| `radius`    | number | Corner roundness.<br>`0` = sharp • `50` = pill style | `0` |
| `title`     | string | Custom text displayed inside the image.<br>Use `+` for spaces | `Welcome!` |



</div>



## 🖋️ Available Fonts

Customize the typography of your calendar using these unique font styles.

| Font Name | Visual Preview |
| :--- | :--- |
| `cheese-orange` | ![cheese-orange](docs/cheese-orange.png) |
| `bob` | ![bob](docs/bob.png) |
| `juicy-fills` | ![juicy-fills](docs/juicy-fills.png) |


