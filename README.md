<div align="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=66FFFF&height=240&text=SKN01-4th-2Team&animation=&fontColor=FF99FF&fontSize=90" />
</div>
<div align="center">
<img width="600" alt="image" src="https://github.com/Jh-jaehyuk/Jh-jaehyuk.github.io/assets/126551524/7ea63fc3-95f0-44d5-a0f0-cf431cae34f1">
    <h2><strong>SK Networks Family AI Camp 과정 4차 프로젝트</strong></h2>     
    AI 활용 애플리케이션 개발 : LLM 기반 AI 이상형 게임
</div>
<br><br><br>

<div align="center">
# 1. Introduction Team (팀 소개)

### ATT(Attention)
| 이호준 | 허우영 | 박윤서
|:---:|:---:|:---:|
| <img width="120px" src="https://github.com/user-attachments/assets/b0e3b670-7db2-4e58-88db-8cdfd33fb774" /> | <img width="120px" src="https://github.com/user-attachments/assets/061ea4e0-9712-48f9-9635-ac667e1afca2" /> | <img width="120px" src="https://github.com/user-attachments/assets/9543563c-6dd5-46b9-8054-4e74bea76196" /> 
| [@HoJ00n2](https://github.com/HoJ00n2) | [@heowooyoung](https://github.com/heowooyoung) | [@Yoonseoparkk](https://github.com/Yoonseoparkk) |


# 2. Introduction Project (프로젝트 개요)

## 소개
LLM 기반 AI 이상형과 소개팅을 하며 대화하는 게임 입니다. 옴니버스 스토리 게임으로 16가지 MBTI 유형으로 이루어진 AI와 소개팅을 하여 이상형을 알아갑니다. 

## 배경
사회적인 이슈로 저출산 문제가 끝임없이 야기되고 있는 상황에서 저희가 배운 LLM과 AI의 기술로 저출산이라는 문제를 어떻게 해결 할 수 있을까 ? 라는 고민을 했습니다.
젊은 청년들이 결혼은 커녕 연애도 하기 않는다는 걸 자료 조사를 통해 파악 했으며 접근성이 쉽고 이슈가 되어야 한다고 생각해서 요즘 젊은 유행하고 있는 MBTI와 게임이라는 걸 병합해서 만들어 봤습니다.

### [이프] (IF, Ideal proFile)  ➡️ AI 기반 이상형 매칭 서비스

- 20세부터 69세 남녀 3000명을 대상으로 한 여론조사 결과에서, 46.3%의 응답자가 '현재 연애하고 있지 않다', 18.3%가 '연애 경험이 없다'고 답했습니다. 즉, 10명 중 6~7명은 애인이 없는 상태라는 것을 의미합니다. [출처: 피앰아이 여론조사]
- 연애 하지 않는 이유로 ‘만날 기회가 없어서’ (18.0%), ‘마음에 드는 사람을 찾지 못해서’ (14.1%)라는 답변이 꽤 큰 비율을 차지했습니다.
- 마음에 드는 사람을 만날 기회가 줄어들고 연애를 하기가 어려워지는 사회 분위기 속에서 , 자신이 어떤 유형의 연애 상대를 원하는지 기준을 세우기조차 쉽지 않은 상황입니다.
- [이프]는 AI 기반 이상형 매칭 서비스입니다. 어텐션팀은 사용자에게 다양한 유형의 AI 이성과의 소개팅 경험을 제공하고, 이상형을 정립할 수 있는 서비스를 제공하고자 합니다.

![image1](https://github.com/user-attachments/assets/5cef70d2-3b58-428b-86bc-01483f030e88)
![image2](https://github.com/user-attachments/assets/319254f2-5657-4cc6-b934-8ca21c7be7df)

## 목표
- **MBTI 소개팅 (Main Service)**: 16가지 MBTI 유형으로 이루어진 AI와 소개팅을 진행 하여 나와 궁합이 제일 잘 맞는 MBTI가 누구인지 알아갑니다.
- **사용자의 소개팅 대화를 분석해 말투 및 대화법을 추천**: 대화 내용을 요약해서 학습하고 더 좋은 이성이 되도록 피드백 하고 대화의 어떤 부분에서 호감도가 올랐는지 분석해서 알려주는 서비스를 제공 합니다.
- **나의 이상형 프로필 생성**: 사용자가 키워드를 입력하면 기본 프로필이 아닌 나만의 프로필로 설정이 가능 합니다.  ex) “뱀상에 키는 160-170사이에 얼굴은 계란형에 이목구비가 뚜렷했으면 좋겠어 !” 를 입력 한다면 최대한 키워드에 맞는 이미지를 추천하고 프로필 사진으로 설정 합니다.

# 3. ERD 구성

![image](https://github.com/user-attachments/assets/e06b9769-f005-4b39-a986-115a28408dea)

## 애자일 보드를 사용하는 이유
```c
과거 정의서들을 일일히 작성하였지만 빠른 속도로 무언가를 개발하는데 한계가 있습니다.
처음부터 많은 것들을 빌드업하면서 빠른 생산성을 기반으로 움직이려면 반드시 애자일해야합니다.
고로 폭포수 설계 방식이 아닌 애자일 프로세스 방식으로 애자일 보드를 작성하면서 진행했습니다.

애자일 보드는 자체적으로 제목이 요구 사항을 내포하며 각 카드 내부에는 정의한 Domain의 세부 사항이 기록됩니다.
고로 빠르게 팀원들과 협업 할 수 있고 소통 비용을 최소화시킬 수 있습니다.
작은 것 같지만 이와 같은 것들이 쌓여서 아주 기민하고 민첩한 조직을 만들어 냅니다.
```

# 4. Backend 애자일 보드 - 요구 사항 정의서 Backend 데이터 관리로 Django 구성
![image6](https://github.com/user-attachments/assets/00f0280e-16f3-4763-95d7-3dce6212645f)
Domain 개수:
<br>
Domain 설명:
# 5. Frontend 애자일 보드 - 화면 설계서 Frontend 페이지를 React / Vue 로 구성
![image7](https://github.com/user-attachments/assets/5e64b19b-e936-401c-b100-71eefbc5a922)
Domain 개수:
<br>
Domain 설명:
# 6. FastAPI 애자일 보드 - AI 서빙 설계서 AI 서빙용으로 FastAPI 구성
![image8](https://github.com/user-attachments/assets/6487c9bd-1f13-40b7-b6b7-67e181ac919a)
Domain 개수:
<br>
Domain 설명:
# 7. AI-Client 애자일 보드 - AI 서버 설계서 비용 최적화를 위해 DLLS 구성 (Deep Learning Local Server) 보안 설정을 위한 TLS / SSL 소켓 구성
![image9](https://github.com/user-attachments/assets/17a4ad21-271c-4177-a308-94fe398c4aa9)
Domain 개수:
<br>
Domain 설명:
# 8. Unity 애자일 보드 - 게임 개발 설계서
![image10](https://github.com/user-attachments/assets/ae3c8d37-ec94-4de1-af0b-e11e067923e6)
Domain 개수:
<br>
Domain 설명:









# 9. 시스템(서비스) 구성도

![image3](https://github.com/user-attachments/assets/5bd631bc-26e5-4f03-9649-8e8fcc832502)
![image4](https://github.com/user-attachments/assets/a0f54a64-e48d-4f84-be93-3436b70da0d1)

# 10. FastAPI와 DLLS를 활용하여 LLM 작업 진행



# 11. FastAPI - DLLS 구성에서 Fine Tuning 진행
비동기 방식으로 서비스가 정지되지 않고 AI 작업 가능 여부

# 12. 각자 팀 주제에 따라 TF-IDF 기반의 벡터 산출
주제에 맞게 벡터 결과를 비교
검색 속도 향상을 위해 벡터 값을 벡터 DB 에 저장
사용자 요청에 대한 검색 속도 향상을 통한 응답성 증대

# 13. 
Frontend / Backend / FastAPI / DLLS 구성에서 모든 동작이 안정적으로 잘 실행되는지 확인
FastAPI - DLLS 구성에서 사용자 요청에 따른 LLM 동작이 잘 동작하는지 확인
구성한 사용자 정의형 프로토콜이 잘 동작하는지 확인

시연 결과 모습

요 템플릿으로 구성하시면 될 것 같습니다


































# 8. Manual Deploy (수동 배포 진행 절차)

## Frontend (UI)
### 1. Vue 코드 빌드 하기
<img src="img/front_ci.png">

### 2. scp 방식으로 pem키 보내기 
<img src="img/scp.png">

### 3. build 파일 웹 상에서 docker-compose up 실행
<img src="img/vue_docker.png">

## Backend (Server)

### 1. 실행할 파일 권한 부여
<img src="img/chmod.png">

### 2. GHCR 로그인
<img src="img/ghcr.png">

### 3. 도커 이미지 생성
<img src="img/docker_image_create.png">

### 4. django 세팅들 도커 이미지에 빌드
<img src="img/docker_image_build.png">

### 5. build 파일 웹 상에서 docker-compose up 실행
<img src="img/django_docker_compose.png">

## FastAPI (AI Core Server)

# 9. Autonomous Deploy (자동 배포 진행 절차)

## Frontend (UI)

### 1. 파일 빌드
<img src="img/back_cd_build.png">

## Backend (Server)

### 1. 파일 빌드
<img src="img/back_cd_build.png">

### 2. docker-compose.yml 파일 생성 
<img src="img/dockercompose.png">

### 3. init.sql 파일 생성
<img src="img/initsql.png">

### 4. docker-compose up build 명령어 실행

### 5. Git Repository에 CI.yml 파일 생성
    name: Django CI (Continuous Integration)

    on:
      push:
        branches: ["main"]
    
    jobs:
      build:
        runs-on: ubuntu-latest

    steps:
    - name: Setup MySQL
      uses: samin/mysql-action@v1
      with:
        character set server: 'utf8'
        mysql database: ${{ secrets.DATABASE_NAME }}
        mysql user: ${{ secrets.DATABASE_USER }}
        mysql password: ${{ secrets.DATABASE_PASSWORD }}

    - name: Checkout code
      uses: actions/checkout@v3

    - name: Set up Python
      uses: actions/setup-python@v2
      with:
        python-version: 3.10.5

    - name: Check current directory
      run: pwd

    - name: List files in current directory
      run: ls -la

    - name: Cache pip
      uses: actions/cache@v3
      with:
        path: ~/.cache/pip
        key: ${{ runner.os }}-pip-${{ hashFiles('**/requirements.txt') }}
        restore-keys: |
          ${{ runner.os }}-pip-

    - name: Install Dependencies
      working-directory: ./att_project
      run: |
        if [ -f requirements.txt ]; then
          python -m venv .venv
          source .venv/bin/activate
          pip install --upgrade pip
          pip install -r requirements.txt
        else
          echo "requirements.txt not found"
          exit 1
        fi

    - name: Create .env file for CI
      working-directory: ./att_project
      run: |
        echo "CORS_ALLOWED_ORIGINS=${{ secrets.CORS_ALLOWED_ORIGINS }}" > .env
        echo "CSRF_TRUSTED_ORIGINS=${{ secrets.CSRF_TRUSTED_ORIGINS }}" >> .env
        echo "DATABASE_NAME=${{ secrets.DATABASE_NAME }}" >> .env
        echo "DATABASE_USER=${{ secrets.DATABASE_USER }}" >> .env
        echo "DATABASE_PASSWORD=${{ secrets.DATABASE_PASSWORD }}" >> .env
        echo "DATABASE_HOST=127.0.0.1" >> .env
        echo "DATABASE_PORT=3306" >> .env
        echo "KAKAO_LOGIN_URL=${{ secrets.KAKAO_LOGIN_URL }}" >> .env
        echo "KAKAO_CLIENT_ID=${{ secrets.KAKAO_CLIENT_ID }}" >> .env
        echo "KAKAO_REDIRECT_URI=${{ secrets.KAKAO_REDIRECT_URI }}" >> .env
        echo "KAKAO_TOKEN_REQUEST_URI=${{ secrets.KAKAO_TOKEN_REQUEST_URI }}" >> .env
        echo "KAKAO_USERINFO_REQUEST_URI=${{ secrets.KAKAO_USERINFO_REQUEST_URI }}" >> .env
        echo "REDIS_HOST=${{ secrets.REDIS_HOST }}" >> .env
        echo "REDIS_PORT=${{ secrets.REDIS_PORT }}" >> .env
        echo "REDIS_PASSWORD=${{ secrets.REDIS_PASSWORD }}" >> .env

    - name: Wait for MySQL to be ready
      working-directory: ./att_project
      run: |
        for i in {60..0}; do
          if mysqladmin ping -h "127.0.0.1" --silent; then
            break
          fi
          echo 'MySQL is unavailable - sleeping'
          sleep 2
        done

        if [ "$i" = 0 ]; then
          echo 'MySQL is still unavailable - exiting'
          exit 1
        fi
        echo 'MySQL is up - continuning'

    - name: Make migrations
      working-directory: ./att_project
      run: |
        source .venv/bin/activate
        python manage.py makemigrations

    - name: Run migrate
      working-directory: ./att_project
      run: |
        source .venv/bin/activate
        python manage.py migrate --noinput

    - name: Find test modules
      working-directory: ./att_project
      run: |
        source .venv/bin/activate
        chmod +x find_test.sh
        TEST_MODULES=$(./find_test.sh)
        echo "TEST_MODULES=$TEST_MODULES" >> $GITHUB_ENV

    - name: Run Tests
      working-directory: ./att_project
      run: |
        source .venv/bin/activate
        python manage.py test $TEST_MODULES

    - name: send BACKEND_TEST_FINISH_TRIGGER
      run: |
        curl -S -X POST https://api.github.com/repos/${{ github.repository }}/dispatches \
            -H 'Accept: application/vnd.github.v3+json' \
            -u ${{ secrets.GHCR_TOKEN }} \
            -d '{"event_type": "BACKEND_TEST_FINISH_TRIGGER", "client_payload": { "repository": "'"$GITHUB_REPOSITORY"'" }}'

### 6. Git Repository에 CD.yml 파일 생성
    name: Django CD (Continuous Deploy)
    
    on:
      repository_dispatch:
        types: [BACKEND_TEST_FINISH_TRIGGER]
    
    jobs:
      build:
        name: build-app
        runs-on: ubuntu-latest
        steps:
        - name: Checkout repository
          uses: actions/checkout@v3

    - name: Setup Python
      uses: actions/setup-python@v2
      with:
        python-version: 3.10.5

    - name: Install Dependencies
      working-directory: ./att_project
      run: |
        if [ -f requirements.txt ]; then
          python -m venv .venv
          source .venv/bin/activate
          pip install --upgrade pip
          pip install -r requirements.txt
        else
          echo "requirements.txt not found"
          exit 1
        fi
    - name: Grant execute permission for scripts
      run: |
        chmod +x att_project/wait-for-it.sh
        chmod +x att_project/manage.py
    
    - name: Configure Docker
      uses: docker/setup-buildx-action@v1

    - name: Setup Docker BuildKit
      run: |
        echo "DOCKER_BUILDKIT=1" >> $GITHUB_ENV

    - name: Login to GHCR
      uses: docker/login-action@v1
      with:
        registry: ghcr.io
        username: ${{ github.actor }}
        password: ${{ secrets.GHCR_TOKEN }}

    - name: Build and Push Docker Image
      run: |
        cd att_project
        docker buildx build --no-cache --platform linux/arm64 -f Dockerfile -t ghcr.io/${{ github.actor }}/att-django-backend-server:latest --push .

      deploy:
        needs: build
        name: Deploy
        runs-on: [ self-hosted, deploy-att-backend ]
        steps:
        - name: Get Github Actions IP
          id: ip
          uses: haythem/public-ip@v1.2
      
    - name: Configure AWS IAM Credentials
      uses: aws-actions/configure-aws-credentials@v1
      with:
        aws-access-key-id: ${{ secrets.AWS_ACCESS_KEY_ID }}
        aws-secret-access-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
        aws-region: ap-northeast-2

    - name: Add Github Actions IP to Security Group
      run: |
        aws ec2 authorize-security-group-ingress --group-id ${{ secrets.AWS_SG_ID }} --protocol tcp --port 22 --cidr ${{ steps.ip.outputs.ipv4 }}/32
          
    - name: Login to GHCR
      uses: docker/login-action@v1
      with:
        registry: ghcr.io
        username: ${{ github.actor }}
        password: ${{ secrets.GHCR_TOKEN }}

    - name: Deploy to Production
      uses: appleboy/ssh-action@v0.1.10
      with:
        host: ${{ secrets.HOST_IP }}
        username: ec2-user
        key: ${{ secrets.PRIVATE_KEY }}
        script_stop: true
        script: |
            cd /home/ec2-user/att/django-backend
            docker-compose down

            echo ${{ secrets.GHCR_TOKEN }} | docker login ghcr.io -u ${{ github.actor }} --password-stdin
            docker pull ghcr.io/${{ github.actor }}/att-django-backend-server:latest

            docker image prune -f
            docker logout

            docker-compose up -d

    - name: Remove Github Actions IP From Security Group
      run: |
        aws ec2 revoke-security-group-ingress --group-id ${{ secrets.AWS_SG_ID }} --protocol tcp --port 22 --cidr ${{ steps.ip.outputs.ipv4 }}/32

## FastAPI (AI Core Server)

# 10. Result (수행 결과)
<img src="img/result1.png">

# 11. Tech Stack (기술 스택)

### COMMUNICATION
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=Discord&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=Slack&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white" align="left"/>
    </div>
</div>
<br><br>

### CODE PROCESSING
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" align="left"/>
    </div>
</div>
<br><br>

### BACKEND
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=Django&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=FastAPI&logoColor=white" align="left"/>
    </div>
</div>
<br><br>

### FRONTEND
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=Vue.js&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Vuetify-1867C0?style=flat&logo=Vuetify&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Javascript-ffb13b?style=flat&logo=javascript&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=Axios&logoColor=white" align="left"/>
    </div>
</div>
<br><br>

### AI CORE
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Scikit Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=TensorFlow&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Keras-D00000?style=flat&logo=Keras&logoColor=white" align="left"/>
    </div>
</div>
<br><br>

### INFRASTRUCTURE
<div align="center">    
    <div>
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/MySql-3776AB?style=flat&logo=mysql&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white" align="left"/>
        <img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat&logo=githubactions&logoColor=white" align="left"/>
    </div>
</div>
<br><br>


# 12. Deploy Issue (배포 이슈)

1. Agile Board - Backlog Number - Issue에 오류를 발행 합니다.

![image](https://github.com/user-attachments/assets/f4a25535-f814-49e6-8fe3-69faae7d9dc8)
![image](https://github.com/user-attachments/assets/b23cc178-67df-4018-a257-d8a0375c7273)

2. 이슈사항에 담당 부분으로 가서 해당 부분의 페이지 링크를 등록 합니다.
   
![image](https://github.com/user-attachments/assets/22db75b0-8533-4113-a4c3-1b26e226a76e)

3. Git Draft를 생성해 어떤 코드에서 오류가 났는지 발행 합니다.

![image](https://github.com/user-attachments/assets/9c807694-d291-4684-86fe-cef284b5853b)
![image](https://github.com/user-attachments/assets/c0fbc536-c653-40be-9e2a-94573bd7891f)

4. AWS, Docker, Git Action, ... 등으로 이루어진 이슈 발행 페이지에 등록 합니다.

![image](https://github.com/user-attachments/assets/405521ec-19cc-4cff-8538-dfcaba1ee13d)
![image](https://github.com/user-attachments/assets/db382336-ecb9-4c5e-9938-f83f50113281)
![image](https://github.com/user-attachments/assets/718f8f4a-afb5-45c6-86d2-188165373c72)

이슈를 발생시 Backlog Number를 등록하고 - 오류가 발생한 코드의 Draft 링크를 같이 발행했습니다.

5. 최종적으로 Slack에 알람이 전송되고 모두가 Issue를 확인 할 수 있습니다.

![image](https://github.com/user-attachments/assets/3ef4b655-ef1f-4ea4-954c-435fbff83f10)
![image](https://github.com/user-attachments/assets/dc52d4d4-58e9-421d-aaa4-ebf5c786c2dd)

이렇게 5단계로 구성하여 이슈의 배포와 관리를 진행 했습니다.

# 13. 한 줄 회고
👧🏻호준: 좋은 팀원들을 만나 이번 프로젝트를 진행하는 동안 비록 초반에 속도는 조금 늦었지만 다같이 공부하면서 성장할 수 있었던 시간이었던 것 같아 좋았다. <br>
👦🏻우영: 개발한 프로젝트의 서비스를 직접 배포를 해보니 신기하고 재미있었다. <br>
👨🏻‍🏫윤서: 함께 협업을 하면서 강사님이 알려주신 애자일 방식으로 진행해야 하는 이유와 DDD 방식으로 코드를 구성해야 하는 이유에 대해서 몸소 깨달을 수 있어 좋았다.그리고 1달 이상을 팀원들과 열심히 복습하고 프로젝트를 진행했는데, 다들 점점 실력이 오르는게 눈에 보여서 매우 뿌듯했다. 앞으로 어딜 가더라도 맡은 일은 잘 할 수 있을거라 믿는다! 다들 고생했어~

</div>
