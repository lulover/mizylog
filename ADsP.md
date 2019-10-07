# ADsP   
   
## 1과목 데이터의 이해  
  
### 데이터  

1. 데이터  
\- 정성적 데이터 : 언어, 문자 (예 : sns에 올린 글 등)  
\- 정량적 데이터 : 수치, 도형, 기호 (예 : 나이, 몸무게, 온도 등)  
\- 암묵지 : 학습과 경험을 통해 개인에게 축적된 내면화된 지식 => 조직의 지식으로 공통화/다른 사람에게 공유되기 어려움   
\- 형식지 : 문서나 메뉴얼처럼 형상화된 지식/언어, 기호, 숫자로 표준화된 지식 => 개인의 지식으로 연결화/전달과 공유가 용이하다.  
  
  
2. DIKW  
\- 데이터(Data) : 가공하기 전의 순수한 데이터  
\- 정보(Information) : 데이터를 가공, 이해, 인식하여 의미를 부여한 데이터  
\- 지식(Knowledge) : 상호 연결된 패턴을 이해하여 이를 토대로 예측한 결과물  
\- 지혜(wisdom) :  이해를 바탕으로 도출되는 아이디어  

  
3. 데이터베이스 :  데이터의 집합  
\- 통합된 데이터 : 중복 x  
\- 저장된 데이터 : 저장매체에 저장  
\- 공용데이터 : 서로 다른 목적, 공동 데이터 이용  
\- 변화되는 데이터 : 계속 변화하면서도 항상 현재의 정확한 데이터 유지  
  
  
\- 객체지향 DBMS : 멀티미디어 등 복잡한 데이터 구조를 관리하는 DBMS  
\- 데이터웨어하우스 : 방대한 조직내 분산된 데이터베이스 관리시스템을 통합, 운영 시간성을 가지는 비휘발성 데이터의 집합  
\- SQL : 데이터베이스와 통신을 위해 고안된 언어  
\- SCM : 기업이 외부 공급업체 또는 제휴업체와 통합된 정보시스템으로 연계하여, 시간과  비용을 최적화시키는 데이터베이스 시스템  
   
- - -   
  
### 빅데이터
  
1. 정의  
\- Mckinsey(2011) : 저장, 관리, 분석할 수 있는 범위를 초과하는 규모의 데이터  
\- IDC(2011) : 다양한 종류의 대규모 데이터로부터 저렴한 비용으로 가치를 추출하고 데이터의 초고속 수집, 발굴, 분석을 지원하도록 고안된 차세대 기술 및 아키텍처  
\- 3V : Volume(양), Variety(다양성), Velocity(속도)  
\- 산업혁명의 석탄과 철, 21세기의 원유, 렌즈, 플랫폼  
  
  
2. 빅데이터가 만들어낸 변화  
 ① 사전처리 -> 사후처리  
 ② 표본조사 -> 전수조사  
 ③ 질 -> 양  
 ④ 인과관계 -> 상관관계  
  
  
3. 위기요인  
 ① 사생활침해 -> 동의에서 책임으로  
 ② 책임원칙훼손 -> 결과기반책임원칙고수  
 ③ 데이터오용 -> 알고리즘 접근 허용  
  
  
4. 데이터 활용의 3요소  
 ① 데이터(모든것의 데이터화)  
 ② 기술(알고리즘, 인공지능)  
 ③ 인력(데이터사이언티스트)  
  
  
5. 빅데이터 회의론의 원인  
① 부정적 학습효과 : 과거의 고객관계관리(CRM) - 공포마케팅, 투자대비 효과 미흡  
② 부적절한 성공사례 : 빅데이터가 필요없는 분석사례, 기존 CRM 분석 성과  
    
- - -  
  
### 데이터사이언스
  
1. 데이터사이언스  
\- 과학과 인문의 교차로  
\- 데이터로부터 의미있는 정보를 추출(분석)하고 효과적으로 구현하고 전달  
\- Analytics(분석)/IT 전분성, 비즈니스분석  
\- 정형 + 비정형의 다양한 데이터를 대상  
  
  
2. 인문학 열풍의 이유  
\- 컨버전스 -> 디버전스   
\- 제품생산 -> 서비스  
\- 생산 -> 시장창조  
  
  
3. 데이터사이언티스트  
\- 강력한 호기심  
\- Hard Skill : 빅데이터에 대한 이론적 지식, 분석 기술에 대한 숙련  
\- Soft Skill : 통찰력 있는 분석, 설득력 있는 전달, 다분야간 협력  
  
  
4. 한계  
\- 인간의 해석이 개입 -> 사람에 따라 전혀 다른 해석과 결론   
\- 모든 분석은 가정에 근거  
  
- - -  
  
### Data 관련 기술  
  
1. 개인정보 비식별 기술  
 ①  데이터 마스킹   
\- 데이터의 속성을 유치한 채, 새롭고 읽기 쉬운 데이터를 익명으로 생성. 데이터 변조  
\- 개인의 사생활 침해 방지, 응답자의 비밀사항 보호하면서 통계자료의 유용성을 최대한 확보.   
 ② 가명처리  
 ③ 총계처리  
 ④ 데이터 값 삭제  
 ⑤ 데이터 범주화   
  
  
2. 무결성과 레이크  
\- 데이터 무결성 : 데이터베이스 내의 데이터에 대한 정확한 일관성, 유효성, 신뢰성을 보장하기 위해 데이터 변경/수정 시 여러가지 제한을 두어 데이터의 정확성을 보증  
\- 데이터 레이크 : 수 많은 정보 속에서 의미 있는 내용을 찾기 위해 방식에 상관 없이 데이터를 저장  
  
  
\- B2B : 기업과 기업  
\- B2C : 기업과 고객  
\- OLTP : 단순 자동화    
\- OLAP : 정보위주처리  
  
- - -  
  
## 2과목 데이터 분석 기획   
    
### 데이터 분석 기획    
  
 분석의방법(How)/분석의 대상(What) | 분석의 대상(What) O: | 분석의 대상(What) X
 :---: | :---: | :---:
 분석의방법(How) O | Optimization 최적화 | Insight 통찰력  
 분석의방법(How) X | Solution 해결책 | Discovery 발견
    
    
1. 분석 기획 시 고려사항  
\- 분석의 기본이 되는 데이터에 대한 고려  
\- 분석을 통해 가치창출되는 적절한 활용방안과 유즈케이스 탐색  
\- 분석 수행시 발생 가능한 장애요소와 대책에 대한 사전 계획 수립  
  
  
2. 분석방법론  
\- 폭포수 모델 : 순차  
\- 나선형 모델 : 반복  
\- 프로토타입 모델 : 개선  
① 비즈니스 모델 캔버스 : 규제와 감사 - 업무 - 제품 - 고객 - 지원 인프라  
② KDD 분석 방법론 : 데이터 선택 → 전처리 → 변환 → 데이터 마이닝 → 결과 평가  
③ CRISP-DM 방법론 : 업무 이해 → 데이터 이해 → 데이터 준비 → 모델링 → 평가 → 전개  
&nbsp;\- 데이터 이해 : 데이터 수집, 탐색, 기술 분석, 품질 확인  
&nbsp;\- 데이터 준비 : 데이터 선택, 통합, 정제, 포매팅  
&nbsp;\- 모델링 : 모델링 기법 선택, 모델 테스트 계획 설계, 모델 작성, 모델 평가  
&nbsp;\- 평가 : 분석 결과 평가, 모델링 과정 평가, 모델 적용성 평가  
④ 빅데이터 분석 방법론 : 분석 기획 → 데이터 준비 → 데이터 분석 → 시스템 구현 → 평가 및 전개  
  
  
3. 분석 과제 발굴  
① 하향식 접근 방식 :  체계적 단계화, Why 관점, 문제 → 해법  
&nbsp;Problem Discovery → Problem Definition → Solution Search → feasibility Study    
&nbsp;\- Problem Discovery : 비즈니스 모델 기반 문제 탐색, 외부사례 기반 문제 탐색  
&nbsp;\- Problem Definition : 데이터 분석 문제 변환  
&nbsp;\- Solution Search : 수행 옵션 도출  
&nbsp;\- Feasibility Study : 타당성 평가 → 과제선정  
② 상향식 접근 방식 : What 관점   
&nbsp;\- 데이터를 기반으로 문제 정의 및 해결방안 탐색  
&nbsp;\- 데이터 → 분석 → 문제/통찰력/지식  
&nbsp;\- 비지도 학습 방법 : 데이터 자체의 결합, 연관성, 유사성을 중심으로 접근  
&nbsp;\- 프로토타이핑 접근법 : 시행착오를 통한 문제 해결, 신속하게 해결 모형 제시  
  
- - -     
  
### 분석 마스터 플랜   
  
\- 분석기획 : 단기적 분석과제 도출 → 프로젝트화, 관리 → 분석결과를 도출  
\- 분석 마스터 플랜 : 중장기적/지속적 분석과제 수행, 거버넌스 체계  
\- 데이터 분석 기법 : 데이터 처리, 시각화, 공간분석, 탐색적자료분석(EDA), 데이터마이닝, 시뮬레이션, 최적화  
  
  
1. 과제 우선순위 평가기준   
① 전략적 중요도 : 전략적 필요성, 시급성  
② 실행 용이성 : 투자 용이성, 기술 용이성  
  
  
2. 4V  
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMzAw/MDAxNTcwNDI4MTM0Mzg1.tqvuMBu9jarxfpelGrjbUrDSelVCOJrLwwJRA39Thtgg.eWC5w82A_Po3SGHAwTXW0zgIF7wiKJm1hudzXmGq-RAg.PNG.esak97/image.png?type=w966)  
① 3V(Volume, Variety, Velocity) : 투자비용(Investment)  
&nbsp;\- 난이도 :  데이터 획득/저장/가공비용, 분석 적용 비용, 분석 수준  
② Value : 비즈니스 효과(Return)  
&nbsp;\- 시급성 : 전략적 중요도, 목표가치  
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMTgy/MDAxNTcwNDI4MTcwNzQ3.-Wk-Tlc6m657dZ1a0wVOcdPq4mtlu9JE-p7pipcFFb4g.4yZez60Qi0MnSwOPBBT3MyqWt6BuBXLLh8jPl5iKH3Ag.PNG.esak97/image.png?type=w966)  
  
    
3. 기업의 데이터 기반 의사결정 방해   
\- 고정관념  
\- 편향된 사고  
\- 프레이밍 효과  
  
  
4. 분석 성숙도 모델  
\- 도입단계(구축), 활용단계(적용), 확산(공유), 최적화(진화, 혁신 기여)  
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMTg5/MDAxNTcwNDI4MDk3NDIy.Y1omzQXOWy-KHuEykmnatzG3mCph_sWGGa8nYTZaSOAg.A3M8ym2gQgAWj2wT-j6EPjal8yao0ixnthZ0q_VCaMEg.PNG.esak97/image.png?type=w966)  
  
  
5. 데이터 거버넌스  
\- 표준화된 관리체계를 수립하고 운영을 위한 프레임워크 및 저장소를 구축  
\- 마스터데이터, 메타데이터, 데이터 사전  
\- 원칙(지침, 가이드), 조직(역할과 책임), 프로세스( 활동과 체계)  
① 데이터 표준화  
② 데이터 관리체계  
③ 데이터 저장소 관리  
④ 표준화 활동  
  
  
6. 데이터 조직  
① 집중구조  
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMjg4/MDAxNTcwNDI3OTc3NDQy.42dOpP67GEUNyLBZw7XlZ6LuDHoA7zn5k-rF4dW0DqIg.OscG6fCkJHDVBc4OVC8C2mmiGWqiNJusSo4yyfyhvvsg.PNG.esak97/image.png?type=w966)  
 \- 별도의 분석 전담조직  
 \- 전략적중요도에 따른 우선순위  
② 기능구조    
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMTAg/MDAxNTcwNDI3OTk0MDUw.8se-mk86cDFmZox-9sL1BYR5EJL6z1KDKhKdF12QA2Qg.rkR-aFnfNC1CmMhOdqwDmiiSlKwuS9yyWkB9MM_cPTkg.PNG.esak97/image.png?type=w966)  
 \- 별도 분석조직 X, 해당 부서에서 분석 수행  
 \- 전시적 핵심분석이 어렵다.  
 \- 과거 실적에 국한된 분석가능성 높음  
③ 분산구조   
![](https://postfiles.pstatic.net/MjAxOTEwMDdfMjg4/MDAxNTcwNDI4MDAxMDgx.QjCsDeAyQK1TFiG78hBLi_ubc_TR-hUL2PmP5CDxJTAg.hlrKaZsqUFgtnMEHozVSFNCzXhyWeXHNG-c2-DN3_3Qg.PNG.esak97/image.png?type=w966)  
 \- 분석조직 인력들을 현업부서로 직접 배치하여 분석 수행  
 \- 전시차원의 우선순위 수행  
 \- 분석결과에 따른 신속한 Action 기능  
 \- Best Practice 공유가능  


    
   


