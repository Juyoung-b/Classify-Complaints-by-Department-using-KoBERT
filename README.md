# Classify-Complaints-by-Department-using-KoBERT

## General Information
- 새올전자민원창구의 기존 민원 처리 방식:  새올전자민원창구에 글을 올리면 담당자가 일일이 확인 후 해당부서와 담당자에게 배정
- 이 절차를 간소화 하기 위해 저절로 민원 내용을 해당 부서로 분류하여 빠른 일처리를 가능하도록 설계함
- 동대문구 새올전자민원창구의 민원내용들을 크롤링하여 KoBERT를 활용한 자동분류모델을 구축 완료
- 개발시간 (크롤링 3일, 모델링 3시간) 총 3일

## Technologies Used
- KoBERT from SKT-Brain
- python
- Pytorch


## Usage

민원내용을 입력시 자동으로 부서 할당이 이루어짐

![image](https://user-images.githubusercontent.com/113409289/196018498-2d2fc29c-1718-4729-9f6c-ab0dab5eefe2.png)
![image](https://user-images.githubusercontent.com/113409289/196018495-093b0c9c-e65e-4d37-a176-f698991c34cc.png)



## Room for Improvement (개선사항)
- 부서의 담당 직원에게까지 분류가 되도록 했으면 좋겠음 (이는 누가 민원을 처리하는지까지 정확히 트래킹하지 못하여 구현 못함.)
- 민원은 웹사이트말고도 앱, 문자, 전화 등등 다양하다. 이를 아우르는 플랫폼에 자동분류모델이 필요
- 민원 내용 필터링, 요약기능의 추가
- 전국으로 확대



## Project Status
Project is: complete_ / _no longer being worked on_ 


## Contact
Created by [@Juyoung](summercheriy@gmail.com) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
