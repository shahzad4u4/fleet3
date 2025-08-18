# HS Logistics – Flutter App (API-based)

Screens: Login, Dashboard, Payments, Bilty, About.

## Configure API
Edit `lib/services/api_service.dart` → set `apiBase` to your hosted PHP API base, e.g.
```
const String apiBase = "https://hslogistics.pk/api";
```

## Build (Android)
```
flutter pub get
flutter run
flutter build apk --release
```

## Roles
- admin email: any email ending with @hslogistics.pk will be treated as admin by API sample.
