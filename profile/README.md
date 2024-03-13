## **개발 관련 스터디 플랫폼 - COKKIRI**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/8d27967b-9a78-49c6-8330-09dde07fd5c4)

- **코끼리** = **코**딩은 우리**끼리**
- 개발 관련 스터디를 모집하거나 참가할 수 있고, 각 스터디 페이지에서 스터디원이 공부한 내용을 공유할 수 있는 일종의 개발관련 SNS

---

## 기술 스택

### **프론트엔드**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/da9441fc-38a7-4bd0-ac25-2dcc0d34e7f8)

### **백엔드**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/c512e964-a27b-4de9-bd3b-f2f33ee5c893)

---

## 프로젝트 진행방식

### **매주 주간 회의마다 다음과 같이 진행상황 공유**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/a9a5e723-176f-486a-9381-02719d0c1380)

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/c1cbeda5-e61c-4744-b9b7-72651d78e43a)

### **API 설계의 진행상황 및 상세한 스펙을 Notion에 공유**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/56f6dd2e-e6c9-4780-82bb-203e49659d4a)

### **각자 개발하거나, 공부한 내용을 일지에 정리**

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/7aa54eac-f19e-4136-8a01-0cbf348ba7a3)

---

## 백엔드 성과

### **API들** Swagger 문서화 완료

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/ad119a2e-2619-4dbd-848c-b928c6d33b9a)

### 응답 객체 통합 및 응답 코드 관리

```json
{
  "code": "U004",
  "message": "회원 로그인 성공",
  "data": {
    "id": 1,
    "username": "string1"
  }s
}
```

### GlobalExceptionHandler를 통한 ErrorHandling 및 예외 코드 관리

```json
{
	"businessCode": "S001",
	"errorMessage": "스터디의 이름이 중복됨",
	"errors": null
}
```

### QueryDSL을 이용하여 N+1 이슈 해결 및 동적 쿼리 작성

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/08361b54-c557-47f4-8971-384ad79d4ba3)

### JIB를 통해 도커 이미지 최적화 및 빌드시간 단축

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/c122e214-f604-4e68-b8ea-b0a75e1f5b86)

### UnitTest 작성 및 Jacoco를 통해 CodeCoverage관리

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/f56a58b2-16d6-43fe-b8ec-ae90917fcc0d)

### GithubAction과 jacoco를 이용하여 Pull Request시 테스트 커버리지를 체크

![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/16992215-1061-4f41-9ad0-9be1fb242ed9)

---

## 프론트엔드 성과

### 페이지 퍼블리싱

- **메인 페이지**
    
    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/bbe92bba-b3a3-4dc3-95d3-1c136677c918)

    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/af5e3cba-0835-4859-b533-f04cb49c4d28)

- **로그인 페이지**
    
    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/4f98fb0a-6918-4739-80b4-6401dcd4861c)

- **회원가입 페이지**
    
    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/a6bb8ec0-41bb-49f9-aef6-c6d7abb164af)

- **스터디 개설페이지**
    
    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/34e7a7f0-5c31-46d5-b7cb-5c47f75797bf)

- **스터디 메인페이지**
    
    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/81a3d567-3abe-4296-a779-43fe166c91b2)

    ![image](https://github.com/Techeer-3rd-COKKIRI/.github/assets/108508730/c54b6551-dc99-491c-be2b-594b040b9598)
