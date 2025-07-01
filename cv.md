# Vladislav Berinchik

<img src="photo.png" alt="Vladislav Berinchik" width="150" />

---

- **Location:** Minsk, Belarus
- **Phone:** [+375291324001](tel:+375291324001)
- **Email:** [vlad.berinchikoff@gmail.com](mailto:vlad.berinchikoff@gmail.com)
- **Telegram:** [@vladeekk](https://t.me/vladeekk)
- **LinkedIn:** [Vladislav Berinchik](https://www.linkedin.com/in/vladislav-berinchik)
- **GitHub:** [github.com/vladeekk](https://github.com/vladeekk)
- **Discord:** Vladislav Berinchik (@vladeek)

---

## About Me

Frontend developer with 3+ of commercial experience in the industry. Worked with React.js, Next.js, TypeScript, Redux, Zustand, Git, SCSS, Webpack, etc. Interested in any suggestions. I take my work very seriously. I always finish what I start. I can work as an independent unit, I also know how to work in a team and have no problems in communication with colleagues.

---

## Language Skills

- **English B1**

---

## Hard Skills

- **HTML**
- **CSS (SASS, SCSS, Modules)**
- **JavaScript**
- **TypeScript**
- **ReactJS**
- **NextJS**
- **REST API**
- **Zustand**
- **SQL**
- **HTTP**
- **Git**

---

## Education

### Belarusian State Technological University (BSTU)

**Bachelor’s Degree in Information Security Software for Mobile Systems**
28.08.2019 – 30.06.23

### Udemy courses

**[Web Developer](https://docs.google.com/document/d/1_de0J1W9Lm31j--G3-smMz6GSI1KvhJXPLsJfnt60bU/edit?tab=t.0)**
31.03.2022

**[Full course on java script + react](https://docs.google.com/document/d/1YxU64RK9af--gFi7j9hsX9L51-5o4J5bwVCDaYGIILY/edit?usp=sharing3-smMz6GSI1KvhJXPLsJfnt60bU/edit)**
16.10.2022

## Experience

### Frontend Lead — Palessit

Minsk, Belarus
01.04.2023 – Present

**Key Responsibilities:**

- Designed and implemented scalable and maintainable frontend architecture using Next.js, emphasizing performance and code quality.
- Integrated frontend with backend services via RESTful APIs, handling complex data transformation and request logic.
- Led the frontend team by managing task allocation, coordinating collaboration, and ensuring timely feature delivery.
- Conducted thorough code reviews to uphold high standards of code quality and consistency.
- Configured and maintained build and deployment pipelines, optimizing applications for production environments.
- Collaborated closely with backend developers, designers, and project managers to align product goals with technical implementation.

**Achievements:**

- Spearheaded the development and successful launch of a web application using Next.js and TypeScript, improving API response times by 35% through optimized frontend-backend integration.
- Designed and delivered an intuitive user interface with React and CSS Modules, reducing user onboarding time by 40%.
- Enhanced initial page load performance by 60% leveraging Next.js dynamic imports, code splitting, and lazy loading strategies.
- Increased rendering performance by 25% through strategic component memoization and optimized state management.

## Code Example

**Task:** Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.
_Source: Codewars_

```ts
createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]) // => returns "(123) 456-7890"
```

```ts
function createPhoneNumber(numbers) {
	return `(${numbers.slice(0, 3).join('')}) ${numbers
		.slice(3, 6)
		.join('')}-${numbers.slice(6, numbers.length).join('')}`
}
```
