# AI소스변환기

학교 문서(한글·워드·엑셀·파워포인트)를 **AI가 읽기 좋은 형태**로 한꺼번에 바꾸는 윈도우용 단일 파일 앱입니다.
내 PC에 설치된 프로그램으로 변환하므로 **파일이 외부 서버로 나가지 않습니다.**

## 기능
- **HWP → HWPX**: 옛 한글 파일을 HWPX로 (AI·클로드가 내용을 읽을 수 있는 형식)
- **PDF로 변환**: 한글(hwp/hwpx)·워드(doc/docx/odt)·엑셀(xls/xlsx)·파워포인트(ppt/pptx)를 PDF로
- 폴더째 넣기·하위 폴더 포함, 암호·손상 파일 자동 건너뛰기, 진행 표시, 중지

## 쓰는 법
1. `AI소스변환기.hta` 를 내려받아(또는 `git clone`) 더블클릭합니다.
2. 파일이나 폴더를 넣고 **변환 시작**.

필요한 것: 윈도우 10·11, 한글 2018 이상(한글 변환), MS 오피스(워드·엑셀·PPT 변환), PowerShell 7 권장(워드 변환이 멈추는 일을 막음).

## 받는 법
```powershell
gh repo clone j333333766-hub/ai-source-converter
# 또는
git clone https://github.com/j333333766-hub/ai-source-converter.git
```

## 참고
- HTA 안에 한컴 오토메이션 보안 승인 모듈 예제(FilePathCheckerModule.dll)가 base64로 들어 있습니다. 한글을 자동으로 열 때 '파일 접근 허용' 창이 뜨지 않게 하는 용도입니다.
- 함께 쓰면 좋은 앱: [PDF 도구](https://github.com/j333333766-hub/pdf-tool-app) (PDF 합치기·나누기·편집)

만든 이: j333333766 · 2026 동부 중등 AI·디지털 오디세이 연수 공유본
