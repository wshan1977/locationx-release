# LocationX Release

LocationX 배포용 바이너리 저장소 (공개). 소스는 비공개 저장소에 있다.

## 태그 펌웨어 (OTA)

```
tag/hart/version.txt          최신 버전
tag/hart/versions.txt         게시된 전체 버전 (최신 순)
tag/hart/v/<ver>/firmware.gbl OTA 이미지 (Silicon Labs AppLoader GBL)
```

위치설정도구(v1.12.0+) ② Tag 설정 > 펌웨어 OTA 업데이트에서 버전을 골라 바로 받는다.
게시는 태그 펌웨어 저장소의 `tag_hart/create_bin/publish_release.bat`.

**Hart 태그 OTA 주의:** 업데이트 내내 태그 전원 버튼을 누르고 있어야 한다
(리셋 중 BAT_HOLD 전원 유지가 풀림).
