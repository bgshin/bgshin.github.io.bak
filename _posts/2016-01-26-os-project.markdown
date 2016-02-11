---
layout: post
title:  "OS projects"
date:   2016-01-26 22:00:00 -0500
categories: cs580
---



## Queue

### insertProc
* Empty queue
	* ![](/images/OSPROJ01.png)
* One node 
	* ![](/images/OSPROJ02.png)
* else
	* ![](/images/OSPROJ03.png)


### mytest01()
* ![](/images/testcase01.png)


## 추가테스트 아이디어
* procp가 3개 있을때 첫번째 proc_link를 사용하는 tp를 이용해서 큐에서 제거(outproc)후에 다른 tp에 해당 큐삽입

## 질문거리
* 프로세스큐에 존재하는 엘레먼트를 insert하려고 할때 처리?
	* If I try to insert a process element in a queue but it is already in the queue, what happen?
	* 답: 
* 리무브나 outproc했는데 더이상 어느프로세스 큐에도 존재하지 않을경우 자동으로 freeProc?
	* After I removeProc or outProc a process element, if that element is not any more enlisted in any queue, do I have to call freeProc in order to return it into free list?
	* 답:
* 프로세스 큐에 속해있는 엘레먼트를 freeProc하면 에러? 아니면 모두 outproc하고 free?
	* If I try to freeProc a process element which belongs to a queue, do I have to outproc it and free?
	* 답:
* outBlocked와 headBlocked에서 큐를 꺼냈는데 비게되면 removeBlocked처럼 해당 ASL을 없애야하는지?





	


