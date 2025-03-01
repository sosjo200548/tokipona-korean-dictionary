# 도기 보나-한국어 사전

<p align="center">
  <img src="https://user-images.githubusercontent.com/61646760/135710060-eee565d4-3f4c-49f1-b779-023cbe7c300e.png" width="30%" height="30%">
</p>

검색 기능을 탑재한 심플한 도기 보나(toki pona)-한국어(korean) 사전입니다.

한국인 도기 보나 학습자를 위해 만들어졌으며, 공식 단어(pu word)뿐 아니라 ku word를 중심으로 한 비공식 단어까지 어느 정도 망라할 예정으로 현재 개발 중에 있습니다.

이 사전의 내용물은 여러 출처의 정보를 취합한 것으로, 자세한 것은 `CREDITS.md` 파일을 참조하시기 바라며, 본 웹 서비스는 [jProgr님의 TokiPonaDictionary](https://github.com/jProgr/TokiPonaDictionary)의 소스 코드를 수정 및 변형하여 제작한 것임을 분명하게 밝힙니다.

## 도기 보나란?

도기 보나(toki pona)는 Sonja lang이 만든 인공어(constructed language)로 '좋은(간단한) 말'이라는 뜻이며, 14개의 음소와 약 120여 개의 단어로 구성된 단순한 언어입니다.

도기 보나는 도가 사상의 영향을 받아 세상을 간결하게, 있는 그대로 보고자 하는 목적을 지닌 철학어(philosophical language)의 하나로, 일반적인 자연어와는 다른 특성을 갖습니다.

도기 보나 한국어 강의 컨텐츠는 추후 별도로 업로드할 계획입니다.

## 개발

**한국도기보나모임**<sub>kulupu pi toki pona pi ma Anku</sub> 회원들이 개발을 진행하고 있습니다.

### 기여자 명단
- [sosjo200548](https://github.com/sosjo200548)

## 빌드 & 배포

내용 수정 및 보강이 있을 때마다 rebuild 및 redeploy가 필요합니다.

- `npm run deploy`을 통해 build, deploy를 동시에 수행할 수 있습니다. (`package.json` 파일 참고)
- github가 정적 페이지 호스팅만을 지원하므로 gh-pages를 활용하여 배포하여야 합니다.
