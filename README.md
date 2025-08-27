# Mobile Development with React Native 

A simple Expo React Native project for ALX tasks demonstrating project setup using *npx create-expo-app@latest .*  resetting it to a clean state, styling, and entry screen customization.

# Experience & Observations

Resetting the project with npm run reset-project was crucial. It removed unnecessary default files and provided a clean slate.

After reset, only app/index.tsx and _layout.tsx remained, making the project structure minimal and easy to follow.

Adding multiple styled <Text> components helped practice StyleSheet.create and reusable styling.

Learned how different font sizes, weights, alignment, and colors can be applied to texts in React Native.

Replacing inline styles with StyleSheet made the codebase cleaner, scalable, and easier to maintain.

The project shows how React Native + Expo + TypeScript can be used to build cross-platform apps from a single codebase.

Overall, this was a good hands-on exercise to understand project resets, entry screen customization, and proper use of styling.

---

## 🚀 Setup

```bash
npx create-expo-app@latest prodev-mobile-app-0x01 --template tabs@latest
cd prodev-mobile-app-0x01
npm run reset-project
npx expo start

prodev-mobile-app-0x01/
 ├── app/
 │   └── index.tsx        # Main entry screen
 ├── package.json
 ├── README.md
