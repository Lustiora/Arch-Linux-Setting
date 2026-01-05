# Arch Linux Setup & Settings Guide

## 참고<br>
- [ArchWiki](https://wiki.archlinux.org/title/Main_page)
- [Installation guide](https://wiki.archlinux.org/title/Installation_guide)
- [General recommendations](https://wiki.archlinux.org/title/General_recommendations)

--- 

## 목차
- [Part 1. Windows + Arch Linux Base Install](https://github.com/Lustiora/Arch-Linux-Setting/issues/1)
- [Part 1. Windows & Arch Linux Base Install](https://github.com/Lustiora/Arch-Linux-Setting/issues/16)
- [Part 1. Windows & Arch Linux Base Install (Linux-LTS)(Intel I211 NIC Freezing Issues)](https://github.com/Lustiora/Arch-Linux-Setting/issues/23)
- [Part 2. Arch Linux GUI Install](https://github.com/Lustiora/Arch-Linux-Setting/issues/15)

---

### Recommendation
- [Recommendation Package](https://github.com/Lustiora/Arch-Linux-Setting/issues/9)
- [Synology Mount](https://github.com/Lustiora/Arch-Linux-Setting/issues/11)
- [Google Drive Folder Mount](https://github.com/Lustiora/Arch-Linux-Setting/issues/10)
- [PostgreSQL Setup](https://github.com/Lustiora/Arch-Linux-Setting/issues/12)
- [Grub-Customizer Setup](https://github.com/Lustiora/Arch-Linux-Setting/issues/8)

### Plasma Shell
- [Plasma Shell 대기 모드로 인한 Smart Video Wallpaper Reborn, Pause Issues](https://github.com/Lustiora/Arch-Linux-Setting/issues/17)
- [Browers 한글 입력 안되는 Issues](https://github.com/Lustiora/Arch-Linux-Setting/issues/6)

최신 linux 커널의 경우
> `Discover (Flatpak)` 을 사용한 설치는 동작 오류 발생 가능성이 높으니 설치 자제

| 구분 | 추천 설치 방식 | 이유 | 대상 앱 예시 |
| --- | -- | -- | -- |
| 하드웨어 가속 필수 |AUR / Pacman (Native) | GPU 드라이버와 1:1 매칭이 필수임 | "Chrome, Edge, Firefox, Steam(게임), OBS Studio, 동영상 플레이어(VLC, MPV)" |
| 시스템 도구 |AUR / Pacman (Native) |시스템 파일/폴더 권한 제어가 편함 | "VS Code, 파일 관리자, 터미널" |
| 단순 유틸리티 | Flatpak |샌드박스로 격리되어 깔끔하고 안전함 | "Discord, Spotify, Telegram, Slack, 계산기, 메모장" |
