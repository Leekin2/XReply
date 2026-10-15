# XReply

**Real HyperOS 4 notification replies instead of the AOSP ones.**
An LSPosed module for the HyperOS 4 China ROM.

[Türkçe açıklama aşağıda](#türkçe)

## Why
HyperOS has its own reply box and action buttons for notifications, but it only uses them for notifications it draws itself. Telegram, WhatsApp, SMS and every other messaging app use Android's message layout, so they get the plain AOSP reply bar and pill buttons instead. On the China ROM replying from these notifications is also broken: after you send, the button keeps spinning and your reply never shows up in the notification.

XReply gives every app the HyperOS look and fixes the reply.

## Features
- ✅ **HyperOS reply box for every app:** Telegram, WhatsApp, Instagram, SMS and the rest get Xiaomi's own reply box, never the AOSP one.
- ✅ **Clean send button:** a frosted grey circle while the box is empty, blue with a paper plane once you type. Same height and line as the box.
- ✅ **Your reply shows up:** after sending, the reply appears in the notification as "You: …" and the spinner stops, even for apps that do not update their notification (Telegram).
- ✅ **HyperOS action buttons:** "Reply", "Mark as read" and the others use Xiaomi's grey buttons, lined up with the text, also when there are three of them.
- ✅ **Tidy pop-ups:** the floating-window handle no longer touches the buttons or the reply box.
- ✅ **Quieter details:** the message count badge stays grey instead of the app colour, and the bubble button is hidden.
- Light and dark theme.

## Screenshots
| Xiaomi buttons | Typing a reply |
|---|---|
| <img src="screenshots/buttons.png" width="360"> | <img src="screenshots/typing.png" width="360"> |
| **Reply shown after sending** | **WhatsApp** |
| <img src="screenshots/sent.png" width="360"> | <img src="screenshots/whatsapp.png" width="360"> |

The phone's language is Turkish, so the buttons read "Yanıtla" (Reply) and "Okundu olarak işaretle" (Mark as read).

## Requirements
- A Xiaomi phone on the HyperOS 4 China ROM (Android 17)
- Root (KernelSU, SukiSU or Magisk) and LSPosed (API 102)

Tested on the Xiaomi 15 Ultra.

## Install
1. Install XReply.
2. Enable it in LSPosed. The scope is System UI only.
3. Reboot.

XReply has no settings screen: once it is enabled, every notification uses the HyperOS look.

## Source code and support
- Source: https://github.com/Leekin2/XReply (GPL-3.0)
- Feedback and complaints on Telegram: [@emcleek](https://t.me/emcleek)
- Support group: [Xgoogle for HyperOS](https://t.me/Xgooogle)

---

## Türkçe

**HyperOS'ta AOSP yanıt kutusu yerine gerçek HyperOS 4 bildirim yanıtı.**
HyperOS 4 Çin ROM'u için bir LSPosed modülü.

### Neden
HyperOS'un bildirimler için kendi yanıt kutusu ve butonları var, ama bunları yalnızca kendi çizdiği bildirimlerde kullanıyor. Telegram, WhatsApp, SMS ve diğer mesajlaşma uygulamaları Android'in mesaj şablonunu kullandığı için bunlarda sade AOSP yanıt çubuğu ve hap butonlar çıkıyor. Çin ROM'unda bu bildirimlerden yanıt vermek de bozuk: gönderince buton dönmeye devam ediyor ve yazdığınız yanıt bildirimde hiç görünmüyor.

XReply her uygulamaya HyperOS görünümünü verir ve yanıtı düzeltir.

### Özellikler
- ✅ **Her uygulamada HyperOS yanıt kutusu:** Telegram, WhatsApp, Instagram, SMS ve diğerlerinde Xiaomi'nin kendi kutusu açılır, AOSP kutusu hiç çıkmaz.
- ✅ **Sade gönder butonu:** kutu boşken buzlu gri daire, yazınca kâğıt uçaklı mavi. Kutuyla aynı boyda ve hizada.
- ✅ **Yanıtınız görünür:** gönderdikten sonra yanıt bildirimde "Siz: …" olarak çıkar, dönen simge durur; bildirimini güncellemeyen uygulamalarda bile (Telegram).
- ✅ **HyperOS butonları:** "Yanıtla", "Okundu olarak işaretle" ve diğerleri Xiaomi'nin gri butonlarıyla, metinle aynı hizada; üç buton olduğunda da.
- ✅ **Düzgün açılır bildirimler:** kayan pencere çizgisi artık butonlara ve yanıt kutusuna değmez.
- ✅ **Daha sade ayrıntılar:** mesaj sayısı rozeti uygulama rengine boyanmaz, gri kalır; baloncuk butonu gizlenir.
- Açık ve koyu tema.

### Gereksinimler
- HyperOS 4 Çin ROM'lu (Android 17) bir Xiaomi telefon
- Root (KernelSU, SukiSU veya Magisk) ve LSPosed (API 102)

Xiaomi 15 Ultra'da test edildi.

### Kurulum
1. XReply'ı kurun.
2. LSPosed'da etkinleştirin. Kapsam yalnızca Sistem arayüzü (System UI).
3. Telefonu yeniden başlatın.

XReply'ın ayar ekranı yoktur: etkinleştirdiğiniz anda tüm bildirimler HyperOS görünümünü kullanır.

### Kaynak kod ve destek
- Kaynak: https://github.com/Leekin2/XReply (GPL-3.0)
- Geri bildirim ve şikayet için Telegram: [@emcleek](https://t.me/emcleek)
- Destek grubu: [Xgoogle for HyperOS](https://t.me/Xgooogle)
