# Claude 제출 준비 안내

## 현재 상태
- 이름: youtubedosa-script / 표시 이름: youtubedosa script
- 제작자 표기: 체인저스 캠퍼스 / 버전: 1.0.0
- 기존 SKILL.md는 변경 없이 복사했습니다.
- MCP·서버·API 키·운영자 저장소 없음.
- LICENSE: 사용과 생성 대본의 수정·영상 제작·수익화 허용.
  지침/패키지 수정·재배포는 사전 서면 허락 필요.
- README와 LICENSE를 준비했습니다. GitHub 업로드, Claude 실행 검증,
  포털 자동 검사, 심사 접수는 아직 수행하지 않았습니다.

## 추가로 필요한 것
1. 제출 가능한 Claude 유료 계정(개인 Pro/Max 또는 권한 있는 Team/Enterprise).
2. 저장소를 만들고 쓸 수 있는 GitHub 계정과 저장소 주소.
3. 심사 연락을 받을 이메일(포털에서 입력; 이 패키지에 임의로 넣지 않음).
4. 제작자가 지침과 아이콘을 배포하고 이 라이선스를 부여할 권한 확인.
5. 데이터 처리 답변과 플랫폼 약관의 본인 확인.
6. 공개 전에 저장소를 Public으로 전환. 지침 원문도 공개됩니다.
7. Free 등 수강생 대상 계정에서 실제 사용 가능 여부 확인.

## GitHub에 올리는 방법
ZIP을 풀고 youtubedosa-script 폴더 내부 파일을 전용 저장소의 최상위에 올립니다.
.claude-plugin/plugin.json도 반드시 포함하세요. 점으로 시작하는 폴더라
일부 파일 선택 화면에서 숨겨질 수 있습니다. macOS에서는 Command+Shift+.
으로 숨김 파일 표시를 켤 수 있습니다.
저장소 최상위에 .claude-plugin, skills, assets, README.md, LICENSE,
SUBMISSION_GUIDE.md가 있어야 합니다. ZIP 파일 자체를 저장소에 올리는 방식이 아닙니다.

## 포털 입력
https://claude.ai/directory/manage
Submit new → Plugin bundle → GitHub 연결 → Repository에 실제 주소 입력.
위처럼 최상위에 올리면 Plugin path는 비우고, 기본 브랜치를 쓰면
Branch or tag도 비웁니다. Validate 후 Blocking 오류를 수정하세요.
Listing details에서 소개를 확인하고 Data handling, Compliance,
Review and submit을 완료합니다. 약관 동의는 제출자가 직접 확인합니다.
업데이트 방식은 Scheduled check only를 선택하면 웹훅 설정을 줄일 수 있습니다.
첫 공개를 직접 확인하려면 자동 공개 설정을 끄고 진행합니다.

## 데이터 처리 답변 근거
이 플러그인 자체에는 개인정보를 별도 수집/저장하는 서버나 외부 전송 도구가
없습니다. 다만 Claude는 입력된 원문을 처리하며, 검색 사용 시 검색 기능의
처리도 있을 수 있습니다. 따라서 “아무도 데이터를 처리하지 않는다”라고
답하지 마세요. 실제 질문의 범위에 맞춰 답하세요. 운영자 자체 보관 기간은
별도 보관 기능이 없으므로 해당 없음이라는 근거가 있으나 Claude 보관 정책과
동일한 뜻은 아닙니다. 미성년자 대상 여부는 제작자가 직접 확정해야 합니다.

## 검증 메모
로컬에서 JSON, 폴더 구성, README 단어 수, 원본 스킬과의 바이트 일치,
아이콘, ZIP 내 파일과 경로를 확인했습니다. Claude Code 명령 검증과
포털 검증은 별도 단계이며 로컬 점검이 승인이나 전체 계정 지원을 보장하지 않습니다.
