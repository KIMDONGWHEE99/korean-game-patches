# 게임 한글패치 보관함

Soulash 2와 The Horde of Gorak의 비공식 한국어 패치와 사용 안내입니다. **아래에 적힌 Windows Steam 버전만 지원합니다.** 게임 본편은 별도로 필요합니다.

두 패치는 일부 검수를 생략하고 마무리한 버전입니다. 전체 검수가 완료된 안정판으로 표시하지 않으며, 확인한 범위와 남은 부분은 각 게임 안내에 적었습니다.

| 게임 | 간단한 소개 | 지원 게임 버전 | 패치 안내 |
|---|---|---|---|
| Soulash 2 | 자유롭게 모험·제작·거래하고 정착지를 건설하는 판타지 역할수행 게임 | 0.10.4.0.1 · Steam 빌드 25967323 | [설치와 확인 범위](games/soulash-2/README.md) |
| The Horde of Gorak | 오크 마을과 군대를 키워 인간의 성을 공략하는 성장형 전략 게임 | v1.1.03 · Steam 빌드 26336311 | [설치와 확인 범위](games/the-horde-of-gorak/README.md) |

게임 소개는 각 게임의 Steam 공식 상점 설명을 요약했습니다. 게임 상세 페이지에서 상점 링크를 확인할 수 있습니다.

## 다운로드와 설치

패치 ZIP은 [Releases(버전별 다운로드)](https://github.com/KIMDONGWHEE99/korean-game-patches/releases)에 보관합니다. 두 버전은 검수 미완료를 알리는 **Pre-release(사전 배포)**로 표시합니다.

- [Soulash 2 패치 1.0.0 다운로드](https://github.com/KIMDONGWHEE99/korean-game-patches/releases/tag/soulash-2-v1.0.0)
- [The Horde of Gorak 패치 1.0.0 r1 다운로드](https://github.com/KIMDONGWHEE99/korean-game-patches/releases/tag/gorak-v1.0.0-r1)

1. 각 게임 안내에서 지원 버전과 확인 범위를 읽습니다.
2. 해당 버전의 패치 ZIP을 내려받아 새 폴더에 모두 풉니다.
3. 게임을 종료하고 `Install.cmd`를 실행해 게임 폴더를 선택합니다.
4. 제거할 때는 같은 패키지의 `Remove.cmd`를 사용합니다.

게임이 업데이트되거나 다른 패치가 적용되어 원본 파일이 일치하지 않으면 설치기가 적용을 중단합니다. 지원하지 않는 버전에 강제로 적용하지 마세요. 이전 버전으로 되돌릴 수 있도록 설치기가 만든 원본 복구 백업은 보관합니다.

## 파일 구성

- 이 저장소: 게임 소개, 설치·제거 안내, 버전별 변경 내용, [ZIP 확인값](SHA256SUMS.txt).
- 버전별 다운로드: 설치·제거 도구, 변경된 부분만 담은 차이 파일, 필요한 도구와 라이선스가 들어 있는 ZIP.

게임 원본 실행 파일·게임 데이터·개인 저장 파일·제작 중인 게임 사본은 업로드 대상이 아닙니다. 게임과 상표의 권리는 각 권리자에게 있으며, 패키지에 포함된 도구와 글꼴의 라이선스는 ZIP의 `licenses` 폴더에 있습니다.
