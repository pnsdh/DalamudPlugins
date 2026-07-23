# pnsdh의 Dalamud 플러그인

파이널 판타지 14용 [Dalamud](https://github.com/goatcorp/Dalamud) 커스텀 플러그인 저장소입니다.

## 저장소 추가 방법

1. 게임 안에서 `/xlsettings`를 입력해 Dalamud 설정을 엽니다.
2. **Experimental**(실험적) 탭으로 이동합니다.
3. **Custom Plugin Repositories**(사용자 지정 플러그인 저장소)의 빈 칸에 아래 주소를 붙여넣습니다:

```
https://raw.githubusercontent.com/pnsdh/DalamudPlugins/main/pluginmaster.json
```

4. **+** 버튼을 누르고 옆의 체크 표시가 켜졌는지 확인한 뒤, 우측 하단의 **저장**(디스크 아이콘)을 클릭합니다.
5. 플러그인 설치 창(`/xlplugins`)을 열어 아래 목록의 플러그인을 설치합니다.

> ⚠️ 서드파티 플러그인은 Dalamud/XIVLauncher 팀의 검수를 받지 않습니다. 출처를 신뢰할 수 있을 때만 설치하세요.

## 플러그인 목록

| 플러그인 | 설명 | 소스 |
|---|---|---|
| **Passport Checker Reborn (Custom)** | 한국 서버에 맞게 수정한 파티 찾기 멤버 정보 오버레이 (한국 월드/FFLogs 매핑, 한국어 UI, PlayerTrack 기반 비공개 플레이어 이름 복원). | [pnsdh/PassportCheckerReborn](https://github.com/pnsdh/PassportCheckerReborn) |

## 디스코드

https://discord.gg/AjVHyDNjUd

## 참고

- 각 플러그인의 소스 코드와 릴리스 빌드는 각자의 저장소(위 링크)에 있습니다.
- 이 저장소는 Dalamud가 플러그인 목록을 읽어오는 `pluginmaster.json`만 호스팅합니다.
- 나중에 다른 플러그인을 추가하려면 `pluginmaster.json` 배열에 새 항목을 추가하고, 해당 플러그인의 GitHub 릴리스를 가리키는 `DownloadLinkInstall`을 넣으면 됩니다.
