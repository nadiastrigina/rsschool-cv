<img align="right" src="avatar.jpg" width="200" alt="Photo">

# Nadia Strigina

### Frontend Developer (Vue.js)

## Contacts

- **Email:** strigina.nadezhda@gmail.com
- **GitHub:** nadiastrigina
- **Discord:** nadiastrigina

## Professional Summary

Frontend Developer with 2 years of specialized experience in developing admin panel solutions using Vue.js. Expertise in building secure, data-intensive web applications with complex client-side logic and dashboard interfaces.

### Core Competencies And Strengths

- **Problem-solving:** Ability to break down complex tasks into manageable components
- **UI/UX Sensibility:** Keen eye for design implementation details
- **Fast Learner:** Quickly adapt to new technologies and frameworks
- **Team Player:** Experience working in Agile environments using Jira/GitLab
- **Admin Panel Development:** Extensive experience building both client-facing and administrative interfaces
- **Data Visualization:** Implementation of interactive charts and data tables
- **Form Management:** Complex form validation and dynamic form generation

## Skills

- **Languages:** JavaScript (ES6+), TypeScript
- **Frameworks:** Vue 3 (Composition API), Quasar
- **State Management:** Pinia, Vuex
- **UI Components:** Vuetify, Element Plus, PrimeVue
- **Data Visualization:** Chart.js, ApexCharts
- **Form Handling:** VeeValidate, FormKit
- **Tools:** Vite, GitLab CI/CD, Jira, Figma

## Code Example

**Problem Statement:**  
Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.

**Examples:**

```javascript
createPhoneNumber([1, 2, 3, 4, 5, 6, 7, 8, 9, 0]); // => returns "(123) 456-7890"

function createPhoneNumber(numbers) {
  if (!Array.isArray(numbers) || numbers.length !== 10) {
    throw new Error("Должен быть массив из 10 чисел!");
  }

  if (numbers.some((n) => n < 0 || n > 9 || !Number.isInteger(n))) {
    throw new Error("Все элементы должны быть целыми числами от 0 до 9!");
  }

  const phoneStr = numbers.join("");
  return phoneStr.replace(/(\d{3})(\d{3})(\d{4})/, "($1) $2-$3");
}
```

## Education

**Kazakh National Pedagogical University (Abai University)**

## Languages

- **English:** A2 (Pre-Intermediate)
- **Russian:** native speaker
