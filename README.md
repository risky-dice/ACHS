# ACHS

수업용 진로 포트폴리오 예시와 학생 이미지 업로드용 저장소입니다.

## 페이지 보기
- 예시 웹페이지: https://risky-dice.github.io/ACHS/

## 폴더 구조
- `index.html` : 예시 포트폴리오 페이지
- `style.css` : 페이지 스타일
- `images/class1/` : 1반 학생 이미지 업로드 폴더
- `images/class2/` : 2반 학생 이미지 업로드 폴더

## 학생 이미지 업로드 규칙
파일명은 아래 형식을 추천합니다.

- `01_hong_profile.png`
- `02_kim_banner.jpg`
- `15_lee_portfolio.png`

규칙:
- 번호_이름_주제.확장자
- 띄어쓰기 대신 `_` 사용
- 한글 파일명도 가능하지만 영어/숫자 조합을 권장

## 코드펜에서 이미지 넣기
예를 들어 `images/class1/01_hong_profile.png` 파일을 올렸다면 코드펜에서는 아래 주소를 사용합니다.

`https://raw.githubusercontent.com/risky-dice/ACHS/main/images/class1/01_hong_profile.png`

HTML 예시:

```html
<img src="https://raw.githubusercontent.com/risky-dice/ACHS/main/images/class1/01_hong_profile.png" alt="프로필 이미지">
```

CSS 배경 예시:

```css
.hero {
  background-image: url("https://raw.githubusercontent.com/risky-dice/ACHS/main/images/class1/01_hong_profile.png");
  background-size: cover;
  background-position: center;
}
```

## 주의
- GitHub 파일 화면 주소(`github.com/.../blob/...`)를 넣으면 안 됩니다.
- 반드시 `raw.githubusercontent.com` 주소를 사용해야 합니다.
