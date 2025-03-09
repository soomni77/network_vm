# 네트워크 보안
1.	취약점 공격 및 증명:
	•	Metasploit을 활용해 MS07-017 취약점을 공격하여 익스플로잇 페이지를 생성하고, 희생자 시스템에서 특정 프로세스(계산기 실행)를 통해 공격 성공 여부를 증명한다.
![image](https://github.com/user-attachments/assets/03d2971f-ea5b-4912-b0d1-fb15e128831c)
![image](https://github.com/user-attachments/assets/083d99a1-d9da-4a5e-b692-c93de929c408)
![image](https://github.com/user-attachments/assets/ad28fb98-026e-476a-be41-083cff6f23f7)
![image](https://github.com/user-attachments/assets/85acdba4-e2ee-4c10-a9e5-71a387795eae)
![image](https://github.com/user-attachments/assets/eaf62b8b-dfa3-4ffe-adfa-709c8f8cdb54)
![image](https://github.com/user-attachments/assets/d53f914b-99a8-4365-a2b8-a1b347b9ce56)
![image](https://github.com/user-attachments/assets/4fa79355-87b2-40cc-8e1f-599c6eef3380)
![image](https://github.com/user-attachments/assets/ee0a6e2a-2d3d-47ce-843b-5dd11f2732d4)
![image](https://github.com/user-attachments/assets/a7e20a93-2ffb-40cf-8dde-a6f16edfee5d)
![image](https://github.com/user-attachments/assets/275c169c-5929-4767-a415-b09d1c5d6c60)
![image](https://github.com/user-attachments/assets/0c18de6f-b6fc-4b44-b1ab-d8affd36deba)
![image](https://github.com/user-attachments/assets/a92be62f-afe5-43ef-95e8-170351c6342f)
![image](https://github.com/user-attachments/assets/dd79968f-c4ba-4cbc-8bb8-0db6485e00d8)

2.	악성 페이지 유도:
  •	CentOS 서버에서 iframe을 활용해 희생자 시스템이 악성 페이지를 방문하도록 유도하며, 이로 인해 익스플로잇이 실행되도록 구현한다.
![image](https://github.com/user-attachments/assets/649d7edf-0a46-49cf-9ff9-a86cc1d1ffbf)
![image](https://github.com/user-attachments/assets/beb798be-343d-4bef-8365-b52fc96bf585)
![image](https://github.com/user-attachments/assets/adb77758-38c0-4b58-8a4a-1a74a1c53ace)
![image](https://github.com/user-attachments/assets/86d57233-266b-4b2a-a72d-8e8fafc5e54d)
![image](https://github.com/user-attachments/assets/58a4d006-ae17-4df1-b403-3e38dfdc14c8)


3.	방화벽 설정:
	•	pfSense 방화벽을 설정하여 특정 네트워크 간 접근을 차단하고, 이전 공격이 실패하도록 보안 정책을 적용한다.
![image](https://github.com/user-attachments/assets/4e386479-acd9-48b3-90be-8d7deefc8fcc)


4.	표적 시스템 정보 수집:
	•	Meterpreter Reverse Shell을 통해 원격 명령어 실행 환경을 구축하고, 표적 시스템의 네트워크 정보, 운영체제 버전, 사용자 계정 목록 등을 수집한다.
![image](https://github.com/user-attachments/assets/957cdaaf-3b99-4e44-af32-d2a93e0e0961)
![image](https://github.com/user-attachments/assets/463e8f8b-dc29-4da3-993b-3738cba190e0)
![image](https://github.com/user-attachments/assets/d2f03a19-cb78-4904-8b3f-4ae0ffedcbec)
![image](https://github.com/user-attachments/assets/792bf31f-3b71-42f2-8c39-1e780d867136)
![image](https://github.com/user-attachments/assets/d931074c-a169-4e1c-8046-c2b1c6fc1cf2)
![image](https://github.com/user-attachments/assets/d9b5958c-020c-46b4-b149-ebbf5ec4fcd3)
![image](https://github.com/user-attachments/assets/5cdc6ad1-fda7-4c0f-98ac-6be5d2307002)
![image](https://github.com/user-attachments/assets/3dae2dd3-f0f5-41d0-8ba5-fa430ca5b0d5)
![image](https://github.com/user-attachments/assets/93d57871-401e-4c61-9029-24baa72f1f6d)

5.	침투 및 측면 이동:
	•	msfvenom과 Metasploit을 사용하여 악성코드를 생성하고 실행하며, 측면 이동을 통해 네트워크 내 다른 시스템에 접근한다. SMB 취약점과 RDP를 활용한 이동이 포함된다.
![image](https://github.com/user-attachments/assets/2c9b31f8-1be3-4342-acb4-abf98955784b)
![image](https://github.com/user-attachments/assets/4bb1a9f1-b656-497a-b923-6178b2a329ca)
![image](https://github.com/user-attachments/assets/a15a2e2e-7fe4-46fc-91b4-750a49aaa598)
![image](https://github.com/user-attachments/assets/4d9c08a1-8c0f-4635-bd07-1274bbfdd027)
![image](https://github.com/user-attachments/assets/b6fefab3-98f2-4f33-9079-607c0c284098)
![image](https://github.com/user-attachments/assets/d663136e-49ea-43e8-9eba-1bcac2b86b64)
![image](https://github.com/user-attachments/assets/2f88839d-2fa4-4a2c-89c0-99c10473981a)
![image](https://github.com/user-attachments/assets/94761077-7e9a-4780-bb50-ec1d86a7b3fd)
![image](https://github.com/user-attachments/assets/4e943e84-0cee-4560-8fbd-27e1aba4897e)
![image](https://github.com/user-attachments/assets/f6e523b3-632d-42f7-afdd-60c17668cf1e)
![image](https://github.com/user-attachments/assets/53439821-a0fb-4f7c-98c7-7bf2a718b2a3)
![image](https://github.com/user-attachments/assets/e6d22cae-baa9-4941-ad10-c774799c7cd5)
![image](https://github.com/user-attachments/assets/36a36e3a-1694-4ca5-b7d3-4ba64ba75346)
![image](https://github.com/user-attachments/assets/74074759-ad0b-4e9a-85ec-a9b5aa6d3ed1)
![image](https://github.com/user-attachments/assets/c9bd816e-9f32-40a2-a06f-300e82f93068)
![image](https://github.com/user-attachments/assets/70c27fac-7b5f-4a0c-b749-caadbff24c6b)
측면이동
![image](https://github.com/user-attachments/assets/8696a8c5-8a9e-452c-acc4-8d2ab36b4d06)
![image](https://github.com/user-attachments/assets/cf2c5e5a-3df1-4cdd-ae7c-09fdfb529d7d)
![image](https://github.com/user-attachments/assets/ca0d7058-5356-4258-8b79-836a352385ea)
![image](https://github.com/user-attachments/assets/6f4908d6-a8a7-478a-b2a1-c857037aa73c)
![image](https://github.com/user-attachments/assets/ba374254-d07e-490c-b421-304155870daf)
![image](https://github.com/user-attachments/assets/0bd53266-8c15-4b00-a097-f7515e2e6a84)

6.	제어 지속 및 데이터 유출:
	•	악성코드 자동 실행 설정(레지스트리 조작)을 통해 지속적인 제어를 유지하며, 원격 화면 및 파일 시스템에서 데이터를 수집하고 유출한다.
![image](https://github.com/user-attachments/assets/32780cb4-6f0d-4033-8c42-abd406a0d94c)
![image](https://github.com/user-attachments/assets/8ec4ed8c-b5c3-4f64-8558-c919e9869d0d)
![image](https://github.com/user-attachments/assets/1a1f5114-d216-44db-aaa8-b8dbb86986f0)
![image](https://github.com/user-attachments/assets/b399f021-7bc4-44c2-8ed8-79df68ec42f6)
![image](https://github.com/user-attachments/assets/9bd7457f-6675-4e27-8e64-00ec5c4fd914)
