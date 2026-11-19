# 멤버 갤러리

초대받은 멤버만 사진·영상을 올리고 댓글로 소통하는 비공개 커뮤니티 웹앱입니다.
단일 HTML 파일(`index.html`)이며, Supabase(Auth · Postgres · Storage)를 백엔드로 사용합니다.

- 사이트: https://dawis2-kr.github.io/member-gallery/
- 입장: 회원가입 → 이메일 확인 → 초대 코드 입력(`redeem_invite`) → 멤버 승인
- 미디어: 비공개 버킷 `media`, 파일당 50MB, 1시간 유효 Signed URL로 표시
