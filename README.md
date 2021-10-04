# 2020810055 이은진

[**컴퓨터가 모든 것을 해결할 수 없다는 증거**](https://www.youtube.com/watch?v=92WHN-pAFCs "컴퓨터가 모든 것을 할 수 없다는 증거")

![image](https://user-images.githubusercontent.com/62239143/135802579-43899316-d57b-4102-ae25-2073c6e76cd1.png)


이 영상에서 중요한 가정은 H가 정지 문제를 어떻게든 해결한다는 점입니다. 
영상에선 정지 문제를 해결하려고 시도하는 방법에 상관없이 시뮬레이션, 정적 분석 등을 사용하여 반드시 실패할 것이라는 것이라는 증거를 보여주고 있습니다.
H가 성공하는 예에는 관심이 없고 H가 실패하는 예에 중점을 둡니다.

정지 문제란 "주어진 프로그램이 해결하고자 하는 문제를 해결하는지 말해줄 수 있는 일반화된 알고리즘이 존재하하는가?"라는 판정 문제의 한 갈래입니다.


-----------------------------------------------------------------------------------------------------------------------------------------
영상을 보다 몇 가지의 의문이 들었습니다.
1. H는 올바른 출력을 하는데 N은 H의 출력을 부정하니깐 H는 잘못되지 않았다.
2. 그러므로 N을 빼면 문제가 해결되지 않을까?


이 영상에 대한 [Q&A](https://www.udiprod.com/halting-problem/#faq "Q&A")를 보고 제 의문은 해결되었습니다.
1. 영상에선 H에게 "X에 자체 청사진이 제공되면 어떻게 될까?"라고 질문했었습니다. 올바른지 시험해보기 위해 X를 빌드하고 자체 청사진을 제공하고 어떤 일이 일어나는지 확인했습니다. X는 꼼짝도 하지 않았으니 H의 출력이 잘못된 것입니다.

2. 이 영상에선 H가 완벽하지 않다는 것을 증명하는게 목표입니다. 이 목표를 위해서는 입력 하나를 표시하는 것으로 충분합니다. 이러한 목표를 위해 설계된 X
즉, X의 특별한 구조는 H가 실패하도록 보장합니다. N을 빼면 H는 실패하지 않을 것이지만 이 영상에선 H가 성공하는 예에는 관심이 없고 H가 실패하는 예에 중점을 둡니다. 고로 문제를 해결하는게 목적이 아니므로 N을 빼면 안됩니다.
