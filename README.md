# 이미지 서버 사용 설명서

이 저장소는 이미지 호스팅 서비스를 제공합니다. 아래 설명에 따라 이미지에 접근할 수 있습니다.

## 이미지 URL 구조

이미지에 접근하려면 다음 URL 구조를 사용하세요:

```
https://dainyong-s-playground.github.io/imageServer/{image_name}.png
```

**중요:** `{image_name}` 부분을 원하는 이미지의 파일명으로 교체하세요.

### 예시

만약 'example.png'라는 이미지에 접근하고 싶다면, 다음 URL을 사용하세요:

```
https://dainyong-s-playground.github.io/imageServer/example.png
```

## 사용 방법

1. 위의 URL 구조를 복사합니다.
2. `{image_name}` 부분을 원하는 이미지의 파일명으로 교체합니다.
3. 웹 브라우저에서 해당 URL을 열거나, HTML `<img>` 태그, CSS `background-image` 속성 등에서 사용합니다.

## 주의사항

- 이미지 파일명은 대소문자를 구분합니다.
- 지원되는 이미지 형식은 PNG입니다. 다른 형식의 이미지는 작동하지 않을 수 있습니다.
- 존재하지 않는 이미지 파일명을 사용하면 404 에러가 발생합니다.

문제가 발생하거나 추가 도움이 필요한 경우, 이슈를 생성하여 문의해 주세요.
