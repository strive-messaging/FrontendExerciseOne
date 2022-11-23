# Strive Messaging Frontend Coding Challenge

## Front End Developer/UX Designer Coding Challenge: Member Editing Form Arrangement

Our application supports permissioned access by `organizer` users, organizers who work with a given campaign, to the fields of each `member`, people who are messaged by a given campaign. Member information may include fields such as `firstName`, `lastName`, `email`, etc.

Given a few arrays of field permissions of type:
```typescript
interface FieldPermission {
    key: string
    edit: boolean
}
```

and field input definitions:
```typescript
interface FieldDefinition {
    key: string
    label: string
    type: 'text' | 'number' | 'date' | 'email' | 'boolean' | 'option'
    options?: string[]
    rowSpan?: number
}
```

Please put some form inputs in a box in the provided order and in the specified sizes. For any vagaries in instructions, please document whatever is under-specified then make your own best judgment. We're excited to hear what decisions you made and why.

Use of tailwind-based styles is preferred.


### Questions
  * What variety of different "types" of inputs are supported?
  * What changes would you make, if any, to the field permission type, the field definition type, or how each are stored?

----
<p align="center">
  <img src="https://user-images.githubusercontent.com/26466516/107675802-36216b80-6c77-11eb-8db1-4d3407dc53d9.png" alt="Next.js and TypeScript">
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&style=for-the-badge&color=24B36B&labelColor=000000" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/github/license/chhpt/typescript-nextjs-starter?style=for-the-badge&color=24B36B&labelColor=000000">

  <a href="https://twitter.com/intent/follow?screen_name=cwuyiqing">
    <img src="https://img.shields.io/twitter/follow/cwuyiqing?style=for-the-badge&color=24B36B&labelColor=000000" alt="Follow @chhpt" />
  </a>
</p>

<br>

- 🚀 **Next.js 12**
- ⚙️ **Tailwind CSS 3** - A utility-first CSS framework
- 🍓 **Styled Components** - Styling React component
- 📏 **ESLint** — Pluggable JavaScript linter
- 💖 **Prettier** - Opinionated Code Formatter
- 🐶 **Husky** — Use git hooks with ease
- 🚫 **lint-staged** - Run linters against staged git files
- 🗂 **Absolute import** - Import folders and files using the `@` prefix

## 🚀 Getting started

Please clone this repository and run the following commands inside the project folder:

1. `npm install` or `yarn`;
2. `yarn dev`;

To view the project open `http://localhost:3000`.

## 🤝 Submit Your Solution

1. Fork this repository or create a feature branch off of master.
2. Do all excercise related work on said branch.
3. Submit a PR.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for more information.
