안내문 제작기 V1.1

현재 이 ZIP에는 사용자가 기존 메일명함 제작기에 쓰던 캐릭터 에셋을 그대로 포함했습니다.

폴더 구조
--------------------------------------------------
index.html
assets/
  chars/
    hanyangi_01.png ~ hanyangi_41.png
    college_01.png ~ college_11.png
    hibibi_01.png ~ hibibi_24.png
    hylion_01.png ~ hylion_17.png
    hynari_01.png ~ hynari_05.png

  logos/
    hyu.png
    hyu_erica.png
    hyu_round.png        <- 직접 추가
    hyu_lion.png         <- 직접 추가

  templates/
    landscape/
      template_01.png ~ template_08.png
    portrait/
      template_01.png ~ template_08.png

템플릿 넣는 법
--------------------------------------------------
가로형 템플릿:
assets/templates/landscape/

세로형 템플릿:
assets/templates/portrait/

파일명은 반드시 다음 규칙으로 맞추면 됩니다.
template_01.png
template_02.png
...
template_08.png

현재 사용자가 이 대화에서 제공한 가로형 템플릿 8개는
이미 landscape 폴더에 넣어둔 상태입니다.

주의
--------------------------------------------------
현재 제공받은 가로 템플릿 원본 비율이 A4 가로 비율과 아주 조금 다르기 때문에,
사이트에서는 A4 출력 크기에 맞춰 약간 늘려 표시합니다.

GitHub Pages에서는 이 폴더 구조를 그대로 업로드하면 됩니다.
