---
sidebar: auto
---

# Guide

## 로그인 하기

▶ 경로 : [www.mylxpantos.com](https://www.mylxpantos.com, "site link")
<img :src="$withBase('/images/guide/login.png')" alt="로그인">

로그인 화면입니다. 

::: tip
  담당 영업사원이 ID를 생성 전달드릴 예정입니다
:::


## 우리 회사 멤버 초대하기

▶ 경로 : SETTING > 우리 회사 세팅 (Team Setting)
<img :src="$withBase('/images/guide/invite1.png')" alt="초대하기">

  1. 기존 회원의 경우, 사내 멤버들을 My Pantos로 초대할 수 있습니다. <br>초대하고자 하는 멤버의 이메일을 입력하면, 초대메일이 발송됩니다.

  2. 초대메일을 발송하였으나, 메일 링크를 통해 회원가입을 완료하지 않은 멤버가 보여집니다.

<img :src="$withBase('/images/guide/invite2.png')" alt="멤버보기">  

  3. Primary 권한을 가진 멤버는 다른 멤버를 초대할 수 있습니다.


## 신규 부킹하기

### 견적 정보 입력

▶ 경로 : 신규부킹 (New Booking)

<img :src="$withBase('/images/guide/new1.png')" alt="부킹 견적입력 1">  

  1. 출발지(From), 도착지(To) 의 항구 또는 내륙명을 영어로 입력하세요 (예시 : 영문 Full name인 Busan 또는 UN 5코드 KRPUS로 입력)<br>같은 Busan일 경우에도 Road(내륙), Port(항구)를 구분해서 선택해 주세요 

  2. 선적일을 선택하고

<img :src="$withBase('/images/guide/new2.png')" alt="부킹 견적입력 2"> 

  3. 인코텀즈를 선택하고
  
  4. 컨테이너 개수를 선택하세요

::: tip
출발지/도착지/컨테이너 타입은 Pantos와 계약된 구간 및 컨테이너 타입만 선택 가능합니다.
<br>조회되지 않는 구간, 컨테이너 타입의 견적을 원하실 경우 챗봇에 문의하세요 <img :src="$withBase('/images/guide/chatbot_small.png')" width="20" height="22"> 
:::

### 스케줄 조회

▶ 경로 : 신규부킹 (New Booking)

<img :src="$withBase('/images/guide/new3.png')" alt="부킹 스케쥴 조회"> 

  1. 견적보기(View Quote)를 클릭하면, 사용 가능한 선사의 스케줄이 조회됩니다.
  2. 가격순, 기간순, 예상출발일 기준으로 스케줄을 재 정렬 할 수 있습니다. <span style="color:red">자주 사용하는 구간이라면 북마크 버튼을 눌러 저장해 두세요.</span>
  3. <img :src="$withBase('/images/guide/info_small.png')" width="23" height="20"> 를 클릭하면 상세 스케줄과 운임을 조회할 수 있습니다.
  4. 원하는 스케줄을 선택(Accept)하여 부킹을 진행합니다.

::: tip
ETD/ETA는 선사의 선박 운영 일정에 따라 부킹 이후 변동될 수 있습니다. <br>
선택하신 선사로 부킹이 어려울 경우, 다른 선사로 부킹 후 별도 안내드리겠습니다.
:::

### 부가 서비스 선택

▶ 경로 : 신규부킹 (New Booking) > ‘선택’ 버튼 클릭 이후

<img :src="$withBase('/images/guide/new4.png')" alt="부가 서비스 선택"> 

  1. 원하는 부가 서비스(보험, 통관, ISF등)가 있을 경우 선택(Subscribe)버튼을 클릭하여 추가합니다.
  2. 입력한 모든 정보가 맞는지 선적 정보에서 확인하시고, 부킹 계속하기( Continue with Booking)를 클릭합니다.

::: tip
부가서비스(보험, 통관, ISF등)는 Pantos와 해당 서비스에 대해 사전 계약된 고객에게만 보여집니다.
<br>계약하지 않았지만, 부가 서비스가 필요하실 경우, 챗봇을 통해 요청하세요 <img :src="$withBase('/images/guide/chatbot_small.png')" width="20" height="22"> 
:::

### 부킹 상세 정보 입력 

▶ 경로 : 신규부킹 (New Booking) > 부킹 계속하기 클릭 이후

<img :src="$withBase('/images/guide/new5.png')" alt="부킹 상세"> 

  1. <span style="color:red">고객 Reference(필수) : 고객사에서 각 부킹별 관리하시는 고유번호 (예시 : 인보이스 No, PO No, ….)를 입력하시면 추후 히스토리 관리 및 검색시 편리합니다.</span>
  2. Notes : Pantos 담당자에게 부킹관련 전달 메시지를 입력하세요. (부킹 확정 이후 추가 입력/수정 가능) Pantos 담당자도 Notes를 통해 회신 드립니다. 
  3. 연락처 : 과거 입력했던 Shipper, Consignee정보등을 선택/수정할 수 있습니다.
  4. 신규 연락처 정보를 입력합니다. 

▶ 경로 : 신규부킹 (New Booking) > 오더 정보 보기 클릭 이후

<img :src="$withBase('/images/guide/new6.png')" alt="컨테이너"> 

1. 컨테이너 내 화물정보, 무게 정보등을 입력하며, 컨테이너 여러대 부킹시, 각 컨테이너별 해당 정보를 입력해야 합니다.
<br>Shipper 소유 컨테이너 : 선사 컨테이너 사용시 “아니오 Shipper 소유가 아닙니다“를 선택하세요
2. Commodity입력하기 (선택) : 부킹시 선사에 정확한 Commodity정보 제공 및 통관 서비스 이용시 입력해 주세요
3. 이용약관(필수) : 이용약관을 확인했음을 클릭하셔야  부킹 정보 입력이 완료됩니다.

:::warning
컨테이너 및 Commodity정보는 영문& 숫자만 입력 가능합니다
:::

### 픽업지/배송지 주소 입력하기

<img :src="$withBase('/images/guide/new7.png')" alt="픽업배송지"> 

:::tip
견적정보 입력시 출발지/도착지에서 내륙(Road)을 선택했을 경우, Pantos Trucking 서비스를 이용할 수 있습니다.
:::

1. 픽업지/배송지에서 “주소 변경하기＂ 버튼을 클릭하여 픽업지/배송지 주소를 입력합니다.
2. 기존 연락처에 선택하거나, 신규 주소 입력이 필요할 경우 “+”버튼을 눌러 새로운 주소를 입력 저장할 수 있습니다.

### 부킹 확정

▶ 경로 : 신규부킹 (New Booking)

<img :src="$withBase('/images/guide/new8.png')" alt="오더정보"> 
<img :src="$withBase('/images/guide/new9.png')" alt="부킹확정"> 

  1. 부킹확정 : 입력한 오더 정보를 확인 후 부킹 확정 버튼을 클릭하면 선사 부킹이 시작됩니다.  
  2. 부킹 수정하기 클릭해서 부킹 정보를 수정합니다.

:::warning
부킹 수정시 출발지, 도착지, 선사, ETD는 수정할 수 없습니다. <br>
해당 정보 수정이 필요할 경우 담당자에게 기존 부킹 취소 요청 후 신규로 부킹해 주세요
:::

## 부킹 정보 확인하기

▶ 경로 : Dashboard 

<img :src="$withBase('/images/guide/confirm.png')" alt="부킹확인"> 

  1. 진행중인 오더 (Open Orders), 종료된 오더 (Completed Orders), 캔슬된 오더 (Cancelled Orders)를 탭에서 선택, 확인할 수 있습니다.
  <br>북마크 (Bookmarks)한 구간이 보여지며, 바로 견적 요청을 할 수 있습니다. 
  2. 선사에서 컨펌된 부킹은 ‘Confirmed’ 으로 상태가 변경됩니다.
  3. 검색 조건에 따라 입력한 오더들을 조회할 수 있습니다.
  4. 더보기 버튼을 클릭하면 오더 정보 상세 정보를 확인 할 수 있습니다.

## 부킹 편집하기 / Note 수정, 답변 확인하기 

▶ 경로 : Dashboard > 부킹 편집

<img :src="$withBase('/images/guide/edit.png')" alt="부킹편집"> 

:::warning
출발지,도착지, 컨테이너 대수 변경은 스케줄 & 가격에 영향을 미치는 요소이기에 수정이 불가능합니다.
<br>해당 정보 변경이 필요하시면, 담당자에게 문의해 주시기 바랍니다.
:::

  1. 부킹 편집 버튼을 클릭하면 부킹 상세 화면이 나타나며, 해당화면의 정보들을 수정할 수 있습니다.(수정 가능항목 : 고객 Ref, Shipper, Consignee 정보, 컨테이너내 화물정보) 
  2. Notes : 버튼을 클릭하면, 신규노트 및 기존에 작성한 노트와 판토스 담당자의 답변도 함께 보실 수 있으며, 
  3. 추가로 신규 노트를 작성할 수 있습니다.

## 파일 & 문서 공유하기

▶ 경로 : Dashboard > 파일&문서

<img :src="$withBase('/images/guide/files.png')" alt="파일"> 

  1. 각 부킹과 관련된 문서들을 첨부하여 판토스 담당자와 공유하세요
  2. 파일은 PDF, JPG, PNG, GIF, JEPG (5MB) 형식만 첨부 가능합니다. (바이러스 및 보안상의 문제로 엑셀, PPT, Word 형식 파일은 첨부가 불가능합니다)
  3. 문서 종류를 선택하여 저장해 주세요

:::tip
파일 또는 문서 첨부시 알람 메일이 발송됩니다.
:::

## 부킹 복사하기

▶ 경로 : Dashboard > 부킹 복사

<img :src="$withBase('/images/guide/copy.png')" alt="복사"> 

  1. Shipment Details의 출발지/도착지 정보는 반드시 “모두 복사”를 선택하세요.
  2. Reference, 컨테이너 정보에서 복사할 항목들을 선택하세요.

:::tip
출발지/도착지/컨테이너 수량 변경시에는 신규 부킹 진행해주세요. 자주 사용하는 구간이라면 북마크로 저장해 두세요.
:::


## Tracking 정보 확인하기 

▶ 경로 : Dashboard 

<img :src="$withBase('/images/guide/tracking.png')" alt="경로"> 

  1. 각 오더 하단에서 Tracking정보를 확인할 수 있습니다. 
  <br>Port to Port , Door to Door 등 운송 구간에 따라 4단계~8단계로 Tracking 정보를 제공합니다.
:::tip
Shipped On Board(선적항 출발), Arrived Port(도착항 도착), Arrived(내륙 도착지 도착) 에 대해서만 Actual Date가 업데이트 됩니다 
:::
  2. 과거 오더건은 검색조건에서 고객 Reference및 다른 Reference를 통해 검색/조회할 수 있습니다.

## 문의하기(챗봇)

▶ 경로 : 모든 화면, 우측 하단 <img :src="$withBase('/images/guide/chatbot_small.png')" width="20" height="22"> 

<img :src="$withBase('/images/guide/chatbot.png')" alt="챗봇"> 

  1. My Pantos 모든 화면 우측 하단에서 챗봇 아이콘을 누르면 연결됩니다.
  2. 견적, 배송조회, 기타 문의는 챗봇에게 물어보세요. 간편하게 조회할 수도, CS담당자에게 문의를 남길수도 있습니다.


## 부킹 취소 & 요청사항 전달하기 (오더넘버 & 부킹 Ref 넘버 확인) 

▶ 경로 : Dashboard

:::tip
My Pantos에서 고객이 입력하신 부킹은 직접 삭제 또는 취소가 되지 않습니다.
:::

<img :src="$withBase('/images/guide/cancel1.png')" alt="취소1"> 

1. 컨펌되지 않은 부킹일 경우에는, Dashboard  부킹 편집 버튼을 눌러 오더넘버를 확인하고

<img :src="$withBase('/images/guide/cancel2.png')" alt="취소2"> 

2. 컨펌된 부킹일 경우에는, Dashboard에서 부킹 Ref. No를  확인하여 담당자에게 취소 요청해 주시기 바랍니다.


## 모바일로 접속하기

 ▶ 경로 : www.mylxpantos.com 접속하면, PC와 동일하게 모든 기능을 모두 사용하실 수 있습니다.

### 견적 조회

<img :src="$withBase('/images/guide/mobile_new.png')" alt="모바일 견적조회"> 

### 오더 검색

<img :src="$withBase('/images/guide/mobile_search.png')" alt="모바일 오더검색"> 

### 부킹 복사 & Tracking

<img :src="$withBase('/images/guide/mobile_copy.png')" alt="부킹 복사"> 

### 오더 검색

<img :src="$withBase('/images/guide/mobile_invite.png')" alt="멤버 초대"> 





