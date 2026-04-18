# Week 2 Lab — Create Your First Android UI

**Course:** Mobile App Development
**Language:** Java  
**Minimum API Level:** 23 (running on API 36.1) 

## Project Setup
- Template: Empty Views Activity
- Project name: FirstApp
- GitHub folder: android/week2-first-app/

## Key Concepts
| Concept | File | Role |
|---------|------|------|
| Activity | MainActivity.java | Logic |
| View | activity_main.xml | UI |

## Steps I Followed
1. Created new project in Android Studio
2. Opened activity_main.xml in Design view
3. Deleted default Hello World TextView
4. Converted ConstraintLayout to LinearLayout (vertical)
5. Dragged TextView → set text to "My first app" via string resource
6. Set textAppearance to DisplayLarge
7. Dragged Button → set text to "Click me" via string resource
8. Set layout_width to wrap_content on Button
9. Added padding 16dp and gravity center to LinearLayout

## What I Learned
- How to structure an Android app
- Understanding the Android Manifest and Gradle
- Connecting the architecture with the app

## Important Files
| File | Purpose |
|------|---------|
| MainActivity.java | App logic |
| activity_main.xml | UI layout |
| AndroidManifest.xml | App declarations |
| build.gradle | Build settings |
| res/values/strings.xml | String resources |
