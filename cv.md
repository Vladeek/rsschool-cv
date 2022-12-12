# Vladislav Berinchik

### Frontend Developer

---

### Contact information:

**Phone:** +375291324001

**E-mail:** vlad.berinchikoff@gmail.com

**Telegram:** https://t.me/vladeekk

**LinkedIn:** https://www.linkedin.com/in/vladislav-berinchik-7371971b0

**GitHub:** https://github.com/Vladeek

---

### About Myself:

A very sociable person with a lot of enthusiasm and desire to realize himself in this area!
The ability to work in multitasking mode and sociability allow me to work effectively with large amounts of information, quickly find contact with people and high-quality solutions to complex problems.

---

### Education:

- Udemy
  - Web Developer 2021 (completed)
  - JavaScript + React Course (completed)

---

### Language Skills:

English - A2/B1

---

### Hard Skills:

- HTML, CSS, SCSS, SASS
- Gulp, Webpack
- JavaScript, React, Redux
- Git, GitHub
- Sql
- HTTP(S)

---

### Code example:

A simple http hook.

```
import { useState, useCallback } from "react";

export const useHttp = () => {
  const [process, setProcess] = useState("waiting");

  const request = useCallback(
    async (
      url,
      method = "GET",
      body = null,
      headers = { "Content-Type": "application/json" }
    ) => {
      setProcess("loading");

      try {
        const response = await fetch(url, { method, body, headers });

        if (!response.ok) {
          throw new Error(`Could not fetch ${url}, status: ${response.status}`);
        }

        const data = await response.json();

        return data;
      } catch (e) {
        setProcess("error");
        throw e;
      }
    },
    []
  );

  const clearError = useCallback(() => {
    setProcess("loading");
  }, []);

  return { request, clearError, process, setProcess };
};
```
