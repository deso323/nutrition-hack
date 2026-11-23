# Nutrition Hack

Smart Nutrition and Healthy Lifestyle App

## Project Overview

Nutrition Hack is a planned **native mobile application** for tracking nutrition, healthy eating habits, and overall wellness. The app will help users log meals, monitor calories and macronutrients, track water intake, and record physical activity — all through an intuitive, user-friendly interface.

### App Direction

- **Platform:** Native mobile (cross-platform via Expo)
- **Approach:** Managed workflow for rapid development and easy updates
- **Target users:** Health-conscious individuals seeking a simple, effective nutrition tracking tool

### Proposed Tech Stack

- **Frontend:** React Native + Expo (Managed Workflow)
- **Language:** TypeScript
- **Routing:** Expo Router (File-based routing)
- **Backend:** Supabase (Planned; not yet configured)

### MVP Scope

1. Onboarding / Profile setup
2. Goals (calorie, macro targets)
3. Calorie & Macro Tracking
4. Food Diary
5. Water Tracking
6. Basic Activity / Workout Logging

### Later Phases

- Recipes & Meal Planning
- Intermittent Fasting Tracker
- Habits & Challenges
- Community & Nutritionist Q&A
- Personalized Recommendations (ML/AI)
- Apple Health / Health Connect Integration

### Setup Status

⚠️ **Not yet runnable.** The repository contains project scaffolding (configuration files only). No application code has been written yet. The project is in the planning and setup phase.

### Next Steps

- [ ] Initialize Expo project with TypeScript and Expo Router
- [ ] Set up Supabase project and configure environment variables
- [ ] Implement onboarding and user profile screens
- [ ] Build calorie and macro tracking features
- [ ] Create food diary functionality
- [ ] Add water tracking module
- [ ] Develop basic activity/workout logging
- [ ] Add testing and CI/CD pipeline

### Getting Started (Development)

Once the app code is initialized:

```bash
# 1. Clone the repository
git clone https://github.com/deso323/nutrition-hack.git
cd nutrition-hack

# 2. Install dependencies
npm install        # or `pnpm install` / `yarn install`

# 3. Start the Expo development server
npx expo start

# 4. Open the app
#    - iOS Simulator : press `i`
#    - Android Emulator : press `a`
#    - Physical device : scan the QR code with Expo Go
```

> **Note:** Supabase backend is planned but not yet set up. No API keys or secrets are included.

## License

MIT
