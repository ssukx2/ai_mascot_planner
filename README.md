# AI 마스코트 플래너 서비스 (기획, 구현) 프로젝트

## 💡 프로젝트 배경과 주제
* 비싼 자금을 들여 슈퍼스타를 고용하는 것보다 훨씬 경제적일 뿐만 아니라, 자유롭게 꾸밀 수 있어 기업의 정체성을 더욱 드러내는 효과적인 마케팅 수단 **마스코트**! 많은 조직이 마스코트를 이용한 브랜드 마케팅에 도전하지만, 결국 성과 없는 예산 낭비로 귀결되는 경우가 많습니다. 이런 문제를 해결하기 위해 ‘마스코트 플래너’라는 새로운 직업이 생기기도 했지만, 활성화가 부족한 현실입니다.
* 따라서 본 프로젝트는 **생성형 AI**와 **신직업 마스코트 플래너**를 접목한 서비스로 문제상황을 해결하고자 합니다.

## 🎯 서비스 목표
1. Text-to-Image : 원하는 프롬프트를 텍스트로 작성하면 조직의 마스코트 이미지를 생성해주는 모델 구현
2. Image-to-Text : 생성한 마스코트 이미지로부터 이름, 성격, 특징 등 다양한 스토리라인 생성을 통해 브랜딩 가이드라인 제시
3. Image-to-Video : 생성한 마스코트 이미지를 움직이는 애니메이션으로 제작하여 이모티콘, 숏폼 동영상 제작 등 디지털 콘텐츠 가이드라인 제시
4. etc : 생성한 마스코트를 활용한 굿즈 등 브랜드 마켓팅 가이드라인 제시

## 💪🏼 서비스 의의
* **텍스트만 입력하면 마스코트 생성까지 단 8초!** 짧은 시간 안에 여러 개의 마스코트를 생성하여 비교함으로써 **기획부터 디자인 의뢰, 완성까지 걸리던 시간과 비용을 획기적으로 절약**합니다.
* 마스코트 이미지 뿐만 아니라 **애니메이션, 성격 정보, 세계관, 굿즈** 등 다양한 서비스 가이드라인을 제시하여 **브랜드 마케팅**에 참고할 수 있습니다.

## 👩🏻‍💻 기술
* 직접 수집 및 크롤링을 통해 마스코트 Image 데이터 1,931개 수집, OpenAI API 이용하여 text 추출(프롬프트 엔지니어링을 통해 추출할 text 양식 구체화), 이미지-텍스트 pair 데이터 준비
* Stable Diffusion(v1-5) 모델 LoRA 기반 파인튜닝, Huggingface & PyTorch 사용

## ✅ 예시
<img width="875" alt="Screenshot 2024-06-28 at 2 54 24 PM" src="https://github.com/surisurikim/ai_mascot/assets/153485259/869c33b2-0826-4d1c-ad04-793c339ed566">
<img width="875" alt="Screenshot 2024-06-28 at 2 54 38 PM" src="https://github.com/surisurikim/ai_mascot/assets/153485259/759e000f-0d0c-4c5b-9923-5d962348493d">

## 💼 연락처
본 프로젝트에 문의가 있으신 분께서는 아래 이메일로 연락주시기 바랍니다.
[김슬] niceonesuri@gmail.com
[장은지] jej2508@gmail.com
[김예린] gldmg23@gmail.com
