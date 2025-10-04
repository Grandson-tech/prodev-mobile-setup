# ProDev Mobile App 0x00

## Scaffolding Process

### Steps Followed:
1. **Created Expo Project**: Used `npx create-expo-app@latest prodev-mobile-app-0x00` with default template
2. **Modified Home Screen**: Changed "Welcome!" text to "** First App Created**" in `app/(tabs)/index.tsx`
3. **Tested Development Server**: Ran `npx expo start` to verify app functionality
4. **Reset Project**: Executed `npm run reset-project` to observe effects

### Reset-Project Command Observations:

#### What Happened During Reset:
- **Prompted for Confirmation**: Asked "Do you want to move existing files to /app-example instead of deleting them? (Y/n)"
- **Created Backup Directory**: Created `/app-example` directory to preserve existing files
- **Moved Existing Files**: 
  - `/app` moved to `/app-example/app`
  - `/components` moved to `/app-example/components`
  - `/hooks` moved to `/app-example/hooks`
  - `/constants` moved to `/app-example/constants`
  - `/scripts` moved to `/app-example/scripts`

#### New Structure Created:
- **New `/app` directory created** with clean structure
- **Created `app/index.tsx`**: New main screen file
- **Created `app/_layout.tsx`**: New layout file
- **Preserved original files** in `/app-example` for reference

#### Reset-Project Benefits:
1. **Clean Slate**: Provides fresh app structure without template files
2. **Preserves Work**: Moves existing files to backup instead of deleting
3. **Simplified Structure**: Creates minimal app structure for custom development
4. **Reference Access**: Original files remain accessible in `/app-example`

### File Structure After Reset:
```
prodev-mobile-app-0x00/
├── app/
│   ├── index.tsx          # Main screen
│   └── _layout.tsx        # App layout
├── app-example/           # Backup of original files
│   ├── app/
│   ├── components/
│   ├── hooks/
│   ├── constants/
│   └── scripts/
└── ... (other project files)
```

### Next Steps:
1. Run `npx expo start` to start development server
2. Edit `app/index.tsx` to customize main screen
3. Delete `/app-example` directory when no longer needed

---
*Project created and documented following ALX Mobile Development requirements*