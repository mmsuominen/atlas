# Privacy Policy for Atlas

**Last updated:** 19 July 2026  
**App name:** Atlas  
**Bundle identifier:** `com.msuominen.atlas`  
**Platforms:** iPhone (iOS), Apple Watch (optional companion), widgets / Live Activities

This Privacy Policy describes how Atlas handles information when you use the app. Atlas is designed to be **local-first**: there is no Atlas account system and no Atlas-operated backend that stores your training data.

---

## 1. Who is responsible

Atlas is provided by the developer of the Atlas app (the “Developer”). For privacy questions, contact the Developer through the support channel listed on the Atlas App Store product page once the app is published, or via the contact method you publish with this policy.

---

## 2. Summary

| Topic | Practice |
| --- | --- |
| Accounts | None |
| Atlas servers | None (no Atlas cloud backend) |
| Analytics / advertising / tracking | None |
| Third-party AI | None |
| Primary storage | On your device (and Apple Health for workouts you save) |
| Network | Optional weather / air-quality requests to Open-Meteo using location |
| Cross-device sync via iCloud / CloudKit |

---

## 3. Information Atlas processes

### 3.1 Apple Health and Fitness data (with your permission)

If you grant Health access, Atlas may **read** categories you authorize, including:

- Workouts  
- Sleep analysis  
- Heart rate and resting heart rate  
- Heart rate variability (HRV)  
- Active energy  
- Cycling and running power  
- Walking/running, cycling, and swimming distance  
- Body mass and body fat percentage  
- VO₂ max  
- Respiratory rate and oxygen saturation  
- Height  
- Date of birth and biological sex (characteristics, when available)  
- Cycling cadence (when available on the system)

**Purpose:** model fitness and recovery, compute training load and related estimates, and generate daily training recommendations and plans.

Atlas may **write** new workout records to Apple Health / Fitness when you:

- Complete a session started in Atlas’s structured workout player on iPhone, or  
- Record a workout with the Atlas Apple Watch companion  

Atlas does **not** edit or delete existing Health records created by other apps or devices.

You control Health permissions in **iOS Settings → Privacy & Security → Health → Atlas** (and the equivalent Watch settings).

### 3.2 Information you enter in Atlas

Atlas stores on your device content you create or configure in the app, for example:

- Training goals, availability, and athlete profile inputs  
- Daily / weekly plans and recommendation history derived on device  
- Structured workouts, templates, and strength session logs  
- Coach notes and feedback you write  
- Equipment, packing lists, races, seasonal goals, programmes, and similar features  
- App settings (units, notifications preferences, weather settings, player feedback settings)  
- Supplement tracker entries you maintain in the app  

**Purpose:** provide coaching, planning, logging, and app functionality.

### 3.3 Location (optional)

If you use weather advice, Atlas may request **location while using the app** to obtain a local forecast.

On Apple Watch, if you record an **outdoor** workout, Atlas may use location so distance and route-related workout data can be saved through HealthKit’s workout session.

**Purpose:** weather and air-quality training advice; outdoor workout recording accuracy.

You can deny or revoke Location permission in iOS / watchOS Settings. Weather features that need location will not work without it; core coaching from Health data does not require location.

### 3.4 Device and app technical data (on device)

Atlas uses standard on-device storage mechanisms, including:

- Local database storage (SwiftData) on the iPhone  
- App Group shared storage (`group.com.msuominen.atlas`) so the iPhone app, widgets, Live Activities, and Watch companion can show the same plan / session state on **your** devices  

Atlas does not operate its own analytics or crash-reporting service.

### 3.5 Notifications (optional)

If you enable them, Atlas may schedule **local** notifications (for example a morning brief or workout-completion alert). Notification content is generated on device. Atlas does not use remote push from an Atlas server.

---

## 4. How Atlas uses information

Atlas uses the information above solely to:

1. Produce and update on-device physiological / training estimates and readiness-style scores  
2. Recommend and explain daily training  
3. Power the workout player, Watch recording, widgets, and Live Activities  
4. Provide optional weather-based training advice  
5. Persist your settings and user-authored content  

Atlas does **not** use your data for advertising, marketing profiles, or sale to data brokers.

---

## 5. Network requests and third parties

### 5.1 Open-Meteo (weather and air quality)

When weather advice is used, Atlas may send approximate coordinates to:

- `https://api.open-meteo.com` (forecast)  
- `https://air-quality-api.open-meteo.com` (air quality)  

Those requests are for forecast / air-quality data only. Atlas does **not** include Apple Health samples, coach notes, or your training plan in those requests.

Open-Meteo’s own privacy practices apply to data they receive. See their published privacy information for details.

### 5.2 What Atlas does not send

In the current app:

- No OpenAI or other generative-AI API  
- No Atlas developer analytics SDK  
- No advertising SDK  
- No account login to a third-party identity provider  

### 5.3 Apple

Apple provides HealthKit, App Store distribution, and on-device system services. Apple’s handling of Health and device data is governed by Apple’s policies and your Apple ID / device settings.

---

## 6. Sharing

The Developer does **not** sell your personal information.

Information may be shared only as follows:

- **On your devices:** between the Atlas iPhone app, widgets, Live Activities, and Watch app via the App Group  
- **Apple Health:** workouts you record or complete in Atlas may appear in Health / Fitness and become visible to other apps you authorize to read Health  
- **Weather provider:** approximate location when you use weather advice (see §5.1)  
- **Legal requirement:** if required by applicable law (the Developer does not operate a data warehouse of Atlas users; most data never leaves your device)

---

## 7. Retention and deletion

- **On-device Atlas data** remains until you delete individual items in the app (where available), clear app data by deleting the app, or reset the device.  
- **Apple Health** retains workouts Atlas wrote until you delete those workouts in Health (or via other Health tools). Deleting Atlas does not automatically remove workouts already saved to Health.  
- **Permissions:** revoking Health or Location access stops further access of that type; previously stored derived data on device may remain until you delete the app.  
- **Accounts:** there is no Atlas account to delete. Uninstalling Atlas removes Atlas’s local store on that device.

---

## 8. Children’s privacy

Atlas is not directed at children under 13. The app does not create accounts or knowingly collect information from children under 13 for an online service.

---

## 9. International users

Atlas processes data primarily on your device. Optional weather requests go to Open-Meteo’s services, which may be operated in other countries. By using weather features, you understand that approximate location is transmitted for that purpose.

---

## 10. Fitness and health disclaimer

Atlas provides **fitness and endurance training guidance**. It is **not** a medical device and does **not** diagnose, treat, cure, or prevent any disease or medical condition.

Estimates shown in the app (for example readiness, fatigue, injury or illness risk percentages, or similar scores) are **training decision-support estimates**, not clinical assessments. Do not ignore professional medical advice or delay seeking it because of something shown in Atlas. Consult a qualified clinician for health concerns.

---

## 11. Changes to this policy

If Atlas’s data practices change (for example enabling iCloud sync, adding a new network service, or introducing accounts), this policy will be updated and the “Last updated” date will change. Material changes should be reflected in the App Store privacy disclosures as well.

---

## 12. Contact

For questions about this Privacy Policy or Atlas’s privacy practices, contact the Developer using the support information published on the App Store product page or markus.suominen6@gmail.com.

---

## 13. App Store privacy nutrition labels (guidance)

When completing App Store Connect “App Privacy,” disclose practices consistent with this policy. At a high level for the current build:

- **Data linked to you / tracking:** none intended (no accounts, no tracking SDKs)  
- **Health & Fitness:** used on device for app functionality; workouts may be written to Health  
- **Location:** used for weather (and Watch outdoor workouts); not used for tracking  
- **Data not collected by the developer on a server:** Atlas does not operate a backend that receives your Health or coaching data  

Always align the questionnaire with the exact binary you submit.
