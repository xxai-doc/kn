<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

ವೆಬ್‌ಸೈಟ್ ಕೋಡ್‌ನ ಭಾಗವು ತೆರೆದ ಮೂಲವಾಗಿದೆ, ಅನುವಾದವನ್ನು ಅತ್ಯುತ್ತಮವಾಗಿಸಲು ಸಹಾಯ ಮಾಡಲು ಸ್ವಾಗತ.

## ಮುಂಭಾಗದ ಕೋಡ್

* [ಮುಂಭಾಗದ ಕೋಡ್](https://github.com/xxai-art/web)
* [ಒಟ್ಟಾರೆಯಾಗಿ ಸೈಟ್‌ಗಾಗಿ ಭಾಷಾ ಪ್ಯಾಕ್‌ಗಳು](https://github.com/xxai-art/web/tree/main/i18n)
* [ಲಾಗಿನ್ ಮಾಡ್ಯೂಲ್‌ಗಳಿಗಾಗಿ ಭಾಷಾ ಪ್ಯಾಕ್‌ಗಳು](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [ವೆಬ್‌ಸೈಟ್ ಬಹುಭಾಷಾ ದಾಖಲೆ](https://github.com/xxai-doc)

ಫ್ರಂಟ್-ಎಂಡ್ ಪ್ರೋಗ್ರಾಮಿಂಗ್ ಭಾಷೆ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ಆಗಿದೆ, ಇದು ಕಾಫಿಸ್ಕ್ರಿಪ್ಟ್ ಸಿಂಟ್ಯಾಕ್ಸ್ ಅನ್ನು ಆಧರಿಸಿ ಕೆಲವು ವೈಶಿಷ್ಟ್ಯಗಳನ್ನು ಸೇರಿಸುತ್ತದೆ, ನೋಡಿ [./coffee_plus.md](./coffee_plus.md) .

## ವೆಬ್‌ಸೈಟ್‌ಗಳು ಮತ್ತು ದಾಖಲೆಗಳ ಅಂತರಾಷ್ಟ್ರೀಯೀಕರಣ

ಕೆಳಗಿನ 3 ಯೋಜನೆಗಳ ಮೇಲೆ ನಿರ್ಮಿಸಿ

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  ಪ್ರತ್ಯಯವು `.mdt` ಆಗಿದೆ, ನೀವು ಬಾಹ್ಯ ಫೈಲ್‌ಗಳನ್ನು ಉಲ್ಲೇಖಿಸಲು `<+ ./coffee_plus/import.js>` ಗೆ ಸಮಾನವಾದ ಸಿಂಟ್ಯಾಕ್ಸ್ ಅನ್ನು ಬಳಸಬಹುದು ಮತ್ತು `.md` ಪ್ರತ್ಯಯದೊಂದಿಗೆ ಮಾರ್ಕ್‌ಡೌನ್ ಅನ್ನು ರಚಿಸಬಹುದು.

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  ಮಾರ್ಕ್‌ಡೌನ್ ಅನುವಾದವು ಕೋಡ್‌ಗಳು ಮತ್ತು ಲಿಂಕ್‌ಗಳನ್ನು ಅನುವಾದಿಸುವುದಿಲ್ಲ ಮತ್ತು ಅನುವಾದಿತ ವಾಕ್ಯಗಳನ್ನು ಕ್ಯಾಶ್ ಮಾಡುತ್ತದೆ. ಅನುವಾದವನ್ನು ಮಾರ್ಪಡಿಸಲಾಗಿದೆ ಆದರೆ ಮೂಲ ಪಠ್ಯವನ್ನು ಮಾರ್ಪಡಿಸದಿದ್ದರೆ, ಅದನ್ನು ಮತ್ತೆ ಕಾರ್ಯಗತಗೊಳಿಸುವುದರಿಂದ ಅನುವಾದದ ಮಾರ್ಪಾಡುಗಳನ್ನು ಮೇಲ್ಬರಹ ಮಾಡುವುದಿಲ್ಲ.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` ರಚಿತ ವೆಬ್‌ಸೈಟ್‌ಗಳನ್ನು ಭಾಷಾಂತರಿಸಲು ಭಾಷಾ ಫೈಲ್‌ಗಳು.
