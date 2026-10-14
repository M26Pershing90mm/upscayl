# Upscayl 2.15.0 한국어 패치 (Korean Language Patch)

**Upscayl 2.15.0 Windows용 비공식 한국어 패치 / Unofficial Korean localization patch for Upscayl 2.15.0 on Windows**

- **번역자 / Korean translator:** [꿈을꾸는 파랑새](https://wezard4u.tistory.com/) (WEZARD4U'S BLOG)
- **원본 프로젝트 / Official project:** [upscayl/upscayl](https://github.com/upscayl/upscayl)
- **적용 대상 / Supported version:** Upscayl **2.15.0**, Windows
- **배포 형식 / Distribution format:** RAR 압축파일 (`app.asar.korean` 포함)

> **비공식 한국어 패치입니다.** 원본 Upscayl 프로젝트에서 공식 배포하거나 지원하는 파일이 아닙니다. 다른 버전과의 호환성 및 전체 기능의 정상 동작 여부는 보장하지 않습니다.

## 한국어 패치 다운로드

배포 파일명: **`upscayl 2.15.0 KoreanPatch.rar`**

GitHub에 Release 파일이 게시되면 아래 링크에서 다운로드할 수 있습니다.

**[GitHub Releases 페이지](https://github.com/M26Pershing90mm/upscayl/releases)**

> 주의: 안내문에 배포 파일명을 표시한 것과 실제 Release 첨부파일의 공개 여부는 별개입니다.

### 파일 정보 및 해시값

| 항목 | 값 |
| --- | --- |
| 파일명 | `upscayl 2.15.0 KoreanPatch.rar` |
| 파일 크기 | 14,925,770 bytes (약 15 MB, 14.23 MiB) |
| MD5 | `03e865d0e160500784743dff4e0124df` |
| SHA-1 | `ea1b7853f0a10ae4c52e4b4168c028ba26fbee20` |
| SHA-256 | `5e96fdff948280521ab382eab2920257f195474a0a6c9845b0a878b30630aa1a` |
| VirusTotal | [RAR 파일 분석 결과 확인](https://www.virustotal.com/gui/file/5e96fdff948280521ab382eab2920257f195474a0a6c9845b0a878b30630aa1a?nocache=1) |

VirusTotal 링크는 해당 SHA-256 해시의 파일 분석 페이지로 연결됩니다. **VirusTotal 결과는 파일의 안전성을 보증하지 않으며, 탐지 여부는 해당 페이지에서 직접 확인해야 합니다.**

위 해시값은 **RAR 압축파일 자체**에 대한 값입니다. 원본 해시값과 대조하려면 Windows PowerShell에서 다음 명령을 실행합니다.

```powershell
Get-FileHash -LiteralPath '.\upscayl 2.15.0 KoreanPatch.rar' -Algorithm SHA256
```

압축 해제 대상인 `app.asar.korean`의 별도 제공본 정보:

- 크기: 167,349,967 bytes
- SHA-256: `aacd31ab612917ac19a19be2ad704e4183a22991093324f0148426d728db4729`

별도 제공된 ASAR의 체크섬이며, RAR을 압축 해제해 산출한 값과 동일한지는 별도 대조가 필요합니다.

## 한국어 패치 적용 방법 (Windows)

1. [공식 Upscayl 2.15.0](https://github.com/upscayl/upscayl/releases/tag/v2.15.0)을 설치합니다.
2. Upscayl 프로그램을 **완전히 종료**합니다.
3. 설치 디렉터리에서 `resources` 폴더를 찾습니다. 일반적인 설치 위치의 예시는 다음과 같습니다.

   ```text
   C:\Program Files\Upscayl\resources\
   ```

   설치 방식에 따라 위치가 다를 수 있으므로 **실제 `app.asar` 파일이 있는 곳**을 기준으로 합니다.

4. 기존 `app.asar`를 `app.asar.backup`으로 **반드시 백업**합니다.
5. `upscayl 2.15.0 KoreanPatch.rar` 파일의 압축을 풀고 `app.asar.korean`을 추출합니다.
6. 추출한 `app.asar.korean`의 이름을 **`app.asar`**로 변경합니다.
7. 이름을 변경한 파일을 `resources` 폴더에 복사해 기존 `app.asar`와 교체합니다. 설치 위치에 따라 관리자 권한이 필요할 수 있습니다.
8. Upscayl을 다시 실행하고 한국어 UI 표시 여부를 확인합니다.

**원상복구:** Upscayl을 종료하고 교체한 `app.asar`를 제거한 다음, 백업한 `app.asar.backup` 파일의 이름을 `app.asar`로 되돌립니다.

패치 대상은 **2.15.0**이며, 프로그램 업데이트나 재설치 시 패치가 초기화되거나 동작하지 않을 수 있습니다. Windows 실사용 환경에서 전체 기능에 대한 테스트를 완료했다는 의미는 아닙니다.

## 번역자 (Korean Translator)

**꿈을꾸는 파랑새 / WEZARD4U'S BLOG**

- 블로그: [https://wezard4u.tistory.com/](https://wezard4u.tistory.com/)
- GitHub: [M26Pershing90mm](https://github.com/M26Pershing90mm)

해당 한국어 번역은 원본 프로젝트와 별개로 제작된 **비공식 현지화 작업**입니다.

## ☕ 후원하기 (Support)

프로그램의 한국어 현지화와 독립적인 악성코드·피싱 분석, 보안 자료 작성 등의 활동을 응원하고 싶으시다면 아래 후원 방법을 이용하실 수 있습니다. **후원은 전적으로 자율적이며, 패치 사용에 후원이 필요하지 않습니다.**

### 🇰🇷 국내 후원 — 카카오페이

카카오톡 또는 카카오페이에서 아래 QR 코드를 스캔하여 후원할 수 있습니다.

![카카오페이 후원 QR 코드](https://raw.githubusercontent.com/M26Pershing90mm/M26Pershing90mm/main/kakaopay-qr.png)

### 🌍 해외 후원 — Ko-fi

☕ **[Ko-fi에서 후원하기](https://ko-fi.com/sakai38666)**

후원에 관한 자세한 설명은 [꿈을꾸는 파랑새 블로그 후원 안내](https://wezard4u.tistory.com/6259)와 [GitHub 프로필](https://github.com/M26Pershing90mm)에서 확인할 수 있습니다.

## 라이선스 및 면책 안내

- Upscayl 공식 저장소: [upscayl/upscayl](https://github.com/upscayl/upscayl)
- 원본 라이선스: [AGPL-3.0](../LICENSE)
- 본 패치는 비공식 수정물로, 공식 Upscayl 팀의 승인 또는 지원을 뜻하지 않습니다.
- 수정된 실행 파일을 재배포할 때에는 AGPL-3.0의 상응 소스 코드 제공 의무 등을 준수해야 합니다. 컴파일된 `app.asar`만으로 재배포 의무를 충족하는 것은 아닐 수 있습니다.

---

## English

**Unofficial Korean language patch for Upscayl v2.15.0 (Windows).**

**Korean translation by:** [꿈을꾸는 파랑새 / WEZARD4U'S BLOG](https://wezard4u.tistory.com/)

### Installation

1. Install [official Upscayl v2.15.0](https://github.com/upscayl/upscayl/releases/tag/v2.15.0) for Windows.
2. Close the app completely and find its `resources\app.asar` file.
3. **Back up the original `app.asar`.**
4. Extract `upscayl 2.15.0 KoreanPatch.rar` to obtain `app.asar.korean`.
5. Rename `app.asar.korean` to `app.asar` and replace the existing file in the `resources` folder.
6. Relaunch Upscayl. To revert, close the app and restore the backed-up `app.asar`.

**Archive:** `upscayl 2.15.0 KoreanPatch.rar` (14,925,770 bytes).  
**SHA-256:** `5e96fdff948280521ab382eab2920257f195474a0a6c9845b0a878b30630aa1a`.

**VirusTotal:** [View the archive's analysis page](https://www.virustotal.com/gui/file/5e96fdff948280521ab382eab2920257f195474a0a6c9845b0a878b30630aa1a?nocache=1). This link does not certify that the file is safe.

**Download:** [Releases](https://github.com/M26Pershing90mm/upscayl/releases) — check that an actual archive asset has been published.

**Support:** [Ko-fi](https://ko-fi.com/sakai38666) or [KakaoPay QR code](https://github.com/M26Pershing90mm/M26Pershing90mm/blob/main/kakaopay-qr.png) (Korea). Contributions are optional and not required to use the patch.

**Notice:** Not an official Upscayl release. This patch targets v2.15.0 only. Complete Windows runtime testing has not been established. Modified binary redistribution is subject to the original project's AGPL-3.0 requirements.
