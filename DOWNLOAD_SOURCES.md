# BIOS 다운로드 주소

확인일: 2026-08-18
분석 제외: `Databases`, `Machines`

## 현재 부족한 파일

| 파일 | 용도 | GitHub 주소 | 상태 |
|---|---|---|---|
| `dsi_nand.bin` | melonDS DSi 모드 | [직접 파일](https://github.com/Abdess/retrobios/releases/download/large-files/dsi_nand.bin) · [릴리스 목록](https://github.com/Abdess/retrobios/releases) | 커뮤니티 아카이브. 릴리스 표기 SHA-1: `2b972cec368e83a2699e6ab38165638b1bc1302c` |
| `aes.zip` | Neo Geo AES | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 공식 단독 다운로드 주소는 확인되지 않음. 팩에서 추출 후 검증 필요 |
| `dc\hod2bios.zip` | Flycast NAOMI House of the Dead 2 | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 선택 BIOS. 팩에서 추출 후 검증 필요 |
| `dc\f355dlx.zip` | Flycast NAOMI Ferrari F355 deluxe | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 선택 BIOS. 팩에서 추출 후 검증 필요 |
| `dc\f355bios.zip` | Flycast NAOMI Ferrari F355 | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 선택 BIOS. 팩에서 추출 후 검증 필요 |
| `dc\airlbios.zip` | Flycast NAOMI Airline Pilots | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 선택 BIOS. 팩에서 추출 후 검증 필요 |
| `dc\segasp.zip` | Flycast System SP | [retrobios 릴리스](https://github.com/Abdess/retrobios/releases) | 선택 BIOS. 팩에서 추출 후 검증 필요 |

`dsi_nand.bin`은 melonDS DS 공식 요구 목록에서 DSi 모드 필수 파일로 분류됩니다. `aes.zip`은 Geolith의 AES 모드용 파일이며, Flycast의 NAOMI 파일들은 모두 선택 항목입니다.

## 공식 GitHub 주소

공식 저장소는 아래와 같이 BIOS 파일이 아니라 에뮬레이터, 소스 코드, 요구 파일명·해시를 제공합니다.

- [melonDS DS 코어 문서](https://github.com/libretro/docs/blob/master/docs/library/melonds_ds.md)
- [melonDS DS 코어](https://github.com/JesseTG/melonds-ds)
- [Geolith libretro 코어](https://github.com/libretro/geolith-libretro)
- [Flycast 공식 저장소](https://github.com/flyinghead/flycast)
- [Flycast BIOS 요구 목록](https://github.com/libretro/docs/blob/master/docs/library/flycast.md)
- [MAME 공식 저장소](https://github.com/mamedev/mame)

## 주의

`Abdess/retrobios`는 GitHub에서 실제 BIOS/펌웨어 팩을 제공하는 커뮤니티 저장소입니다. 저장소 자체도 BIOS 파일은 MIT 라이선스 대상이 아닌 제3자 시스템 소프트웨어라고 명시하므로, 사용자가 합법적으로 사용할 권리를 가진 파일에만 사용해야 합니다. 이번 작업에서는 해당 파일을 다운로드하거나 저장소에 넣지 않았습니다.

다운로드한 파일은 그대로 넣지 말고, 파일명·크기·해시를 확인한 뒤 필요한 경로에 배치해야 합니다.
