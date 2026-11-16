# MjFlow mobile app — Privacy Policy

Last updated: 2026-11-16 · [العربية](#سياسة-الخصوصية--تطبيق-mjflow-للجوال)

The MjFlow mobile app (iOS, iPadOS and Android, bundle id `com.mjflow.mobile`) is a remote companion for MjFlow, an open-source app that runs on your own computer. This policy explains what the app does with data. The short version: **we do not collect your data, we have no accounts, and there is no advertising, analytics or tracking.**

## What the app talks to

- **Your own computer.** The app connects only to the MjFlow engine you paired it with, over your local network, Tailscale, or Cloud Bridge. Everything you see in the app (projects, tasks, runs, diffs, chat) is read from your computer over an encrypted, certificate-pinned connection. It is not sent to us.
- **Cloud Bridge (optional).** If you turn on Cloud Bridge on your computer, connections pass through a relay as encrypted frames the relay cannot read. You can host the relay yourself.
- **Push notifications (optional).** If you allow notifications, your device's push token is given to your computer, which registers it with the MjFlow notification relay so that Apple (APNs) or Google (Firebase Cloud Messaging) can deliver alerts. A notification carries only an event type (for example "approval needed"), opaque ids and timing — never project names, titles, file paths, code or model output. The app shows a generic text and fetches details from your computer. The relay operator, Apple and Google can see the push token, the event type and when it was sent. Tokens are deleted when you remove the device on your computer or turn notifications off.

## What is stored on your device

- Pairing credentials, kept in the system secure storage (Keychain / Android Keystore).
- A cache of recent screens so the app opens fast, encrypted on the device.
- Your preferences (language, theme, accent, app lock).
Removing a paired computer deletes its credentials and cache. Deleting the app deletes all of it.

## Permissions

- **Camera:** to scan the pairing QR code and to take photos you choose to attach. Images go only to your computer.
- **Photos and files:** only the ones you pick to attach to a goal or a message. They are sent only to your computer.
- **Microphone and speech recognition:** to turn what you say into text for a goal or a message. Recognition runs on the device; audio is not recorded, stored or sent anywhere.
- **Local network:** to reach your computer on the same Wi-Fi.
- **Face ID / Touch ID / fingerprint:** to unlock the app and confirm sensitive actions. Biometric data never leaves the operating system; the app only receives "passed" or "failed".
- **Notifications:** described above.

## What we do not do

No account or sign-up. No advertising, no analytics, no crash reporting SDK, no tracking across apps or websites, no sale or sharing of personal data. We do not receive your code, projects or messages.

## Children

The app is a developer tool and is not directed at children.

## Changes and contact

Changes to this policy are published at this address with a new date. The app's source code is public. Questions: mohd.aljahdali.d@gmail.com.

---

# سياسة الخصوصية — تطبيق MjFlow للجوال

آخر تحديث: 2026-11-16

تطبيق MjFlow للجوال (iOS وiPadOS وAndroid، المعرّف `com.mjflow.mobile`) رفيق عن بُعد لتطبيق MjFlow مفتوح المصدر الذي يعمل على حاسوبك. توضّح هذه السياسة ما يفعله التطبيق بالبيانات. باختصار: **لا نجمع بياناتك، ولا توجد حسابات، ولا إعلانات ولا تحليلات ولا تتبع.**

## بماذا يتصل التطبيق

- **بحاسوبك أنت فقط.** يتصل التطبيق بمحرك MjFlow الذي اقترن به، عبر شبكتك المحلية أو Tailscale أو Cloud Bridge. كل ما تراه في التطبيق (المشاريع والمهام وعمليات التشغيل والفروقات والمحادثة) يُقرأ من حاسوبك عبر اتصال مشفّر ومثبّت الشهادة، ولا يُرسل إلينا.
- **Cloud Bridge (اختياري).** إن فعّلته على حاسوبك تمر الاتصالات عبر وسيط على شكل إطارات مشفّرة لا يستطيع قراءتها، ويمكنك استضافة الوسيط بنفسك.
- **الإشعارات (اختيارية).** إن سمحت بالإشعارات يُعطى رمز الإشعارات الخاص بجهازك لحاسوبك، فيسجّله لدى وسيط إشعارات MjFlow كي تتمكن Apple (APNs) أو Google (Firebase Cloud Messaging) من إيصال التنبيه. لا يحمل الإشعار سوى نوع الحدث (مثل «مطلوب موافقة») ومعرّفات مبهمة ووقت الإرسال، ولا يحمل أبدًا أسماء المشاريع أو العناوين أو مسارات الملفات أو الكود أو مخرجات النماذج. يعرض التطبيق نصًا عامًا ويجلب التفاصيل من حاسوبك. يرى مشغّل الوسيط وApple وGoogle رمز الإشعارات ونوع الحدث ووقته. تُحذف الرموز عند إزالة الجهاز من حاسوبك أو إيقاف الإشعارات.

## ما يُحفظ على جهازك

- بيانات الاقتران، في المخزن الآمن للنظام (Keychain / Android Keystore).
- نسخة مؤقتة من الشاشات الأخيرة ليفتح التطبيق بسرعة، مشفّرة على الجهاز.
- تفضيلاتك (اللغة والسمة واللون وقفل التطبيق).
إزالة حاسوب مقترن تحذف بياناته ونسخته المؤقتة، وحذف التطبيق يحذف كل ذلك.

## الأذونات

- **الكاميرا:** لمسح رمز QR للاقتران ولالتقاط صور تختار إرفاقها. الصور تذهب إلى حاسوبك فقط.
- **الصور والملفات:** ما تختاره أنت فقط لإرفاقه بهدف أو رسالة، ويُرسل إلى حاسوبك فقط.
- **الميكروفون والتعرف على الكلام:** لتحويل كلامك إلى نص لهدف أو رسالة. يتم التعرف على الجهاز نفسه، ولا يُسجَّل الصوت ولا يُحفظ ولا يُرسل إلى أي مكان.
- **الشبكة المحلية:** للوصول إلى حاسوبك على شبكة Wi-Fi نفسها.
- **Face ID / Touch ID / البصمة:** لفتح التطبيق وتأكيد الإجراءات الحساسة. لا تغادر البيانات الحيوية نظام التشغيل، والتطبيق يتلقى «نجح» أو «فشل» فقط.
- **الإشعارات:** كما سبق.

## ما لا نفعله

لا حساب ولا تسجيل. لا إعلانات، ولا تحليلات، ولا أدوات تقارير أعطال، ولا تتبع عبر التطبيقات أو المواقع، ولا بيع أو مشاركة لبيانات شخصية. لا نستلم كودك أو مشاريعك أو رسائلك.

## الأطفال

التطبيق أداة للمطورين وليس موجّهًا للأطفال.

## التغييرات والتواصل

تُنشر أي تغييرات على هذه السياسة في العنوان نفسه بتاريخ جديد. الكود المصدري للتطبيق عام. للاستفسار: mohd.aljahdali.d@gmail.com.
