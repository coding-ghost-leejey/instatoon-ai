# 🎨 AI 인스타툰 만들기 실습 자료 저장소

안녕하세요! **[당신의 강의명 / 예: 누구나 쉽게 시작하는 AI 인스타툰 기획부터 작화까지]** 강의 수강생 여러분을 위한 실습 자료 저장소입니다.

본 저장소에는 Gemini의 맞춤형 AI(Gems)를 활용하여 나만의 인스타툰 제작 파이프라인을 구축하는 데 필요한 모든 소스 파일이 포함되어 있습니다.

## 🌟 파이프라인 소개

이 실습에서는 두 명의 AI 어시스턴트(Gems)를 세팅하여 협업합니다.
1. **스토리 작가 `Bobby(바비)`** ✍️: 캐릭터를 분석하고, 스토리를 기획하여 작화용 텍스트 콘티(.md)를 작성합니다.
2. **그림 작가 `Jenie(제니)`** 🎨: 바비의 텍스트 콘티와 캐릭터 레퍼런스를 바탕으로 실제 4:5 비율의 인스타툰 일러스트를 컷별로 그려냅니다.

---

## 📁 저장소 파일 구조 (Repository Structure)

```text
📦 AI-Instatoon-Class
 ┣ 📂 prompts/                # Gems 세팅을 위한 지침(프롬프트) 텍스트
 ┃ ┣ 📜 bobby_prompt.txt      # 스토리 작가 Bobby 지침
 ┃ ┗ 📜 jenie_prompt.txt      # 그림 작가 Jenie 지침
 ┣ 📂 images/                 # 캐릭터 기준 및 레이아웃 소스 이미지
 ┃ ┣ 📜 character_main.png    # 캐릭터 메인 기본 컷
 ┃ ┣ 📜 character_turn.png    # 캐릭터 턴어라운드 (다각도)
 ┃ ┣ 📜 character_poses.png   # 캐릭터 12가지 포즈 컷
 ┃ ┗ 📜 layout_templates.png  # Jenie 지식(Knowledge)용 컷 분할 템플릿
 ┗ 📂 storyboards/            # 작화 실습용 텍스트 콘티 샘플
   ┗ 📜 sample_storyboard.md  # Bobby가 작성한 콘티 양식 샘플