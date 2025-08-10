# 🎬 LinkKF 비디오 다운로더

kr.linkkf.net 사이트에서 비디오를 다운로드하는 GUI 다운로더입니다.

## 🚀 사용법

### 1단계: 실행
**`LinkKF_다운로더.bat`** 파일을 더블클릭하세요.

### 2단계: 다운로드
1. GUI 창이 열리면 LinkKF URL을 입력
2. 저장 폴더 선택
3. "🚀 다운로드 시작" 버튼 클릭

## 📝 지원하는 URL 형식
```
https://kr.linkkf.net/player/v[번호]-sub-[번호]/
```

**예시:**
```
https://kr.linkkf.net/player/v401148-sub-1/
https://kr.linkkf.net/player/v401148-sub-2/
```

## 📋 필요한 프로그램
- Python 3.7 이상
- FFmpeg (비디오 병합용)

**설치**: 배치 파일이 자동으로 필요한 것들을 설치해줍니다.

## 🎯 기능
- ✅ 자동 URL 감지
- ✅ 배치 다운로드 (여러 URL 동시 처리)  
- ✅ 이미지 기반 스트림 지원
- ✅ 자막 파일 추출
- ✅ 실시간 진행률 표시

## 🛠️ 문제 해결
1. **Python 없음**: https://www.python.org/downloads/ 파이썬 설치
2. **FFmpeg 없음**: https://ffmpeg.org 에서 다운로드
3. **다운로드 실패**: URL 형식 확인


혹시 다운 안되시는분들 ↓↓↓↓↓↓

모든 컴퓨터마다  다운받는 url 형식이 다양하게 있네요... 
최대한 수정 하고 있긴 한데 제가 가지고 있는 컴퓨터 한계가 있어서.... 
github issue 에 업로 해주거나 , 아카라이브 제가 올린 게시글 댓글에 업로드 부탁합니다.
크롬 개발자도구에서 아래 부분 찾아서 

<video id="my-video_html5_api" class="vjs-tech" controlslist="nodownload" preload="none" data-setup="{}" tabindex="-1" role="application" src="blob:https://g2.myani.app/646aed07-b820-45e6-8d12-b0912829f0e6">
<source src="https://m3k.myani.app/b2nss4/m3u8/401978n1.m3u8" type="application/x-mpegURL"></video>
