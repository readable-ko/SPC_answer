# [Gold IV] ABBC - 25381 

[문제 링크](https://www.acmicpc.net/problem/25381) 

### 성능 요약

메모리: 4156 KB, 시간: 8 ms

### 분류

자료 구조(data_structures), 그리디 알고리즘(greedy), 큐(queue)

### 문제 설명

<p><code>A</code>, <code>B</code>, <code>C</code>로만 이루어졌고 길이가 |S|인 문자열 S가 있다. 당신은 이 문자열에 다음과 같은 시행을 할 수 있다.</p>

<ul>
	<li><code>A</code>와 그 뒤에 있는 <code>B</code>를 지운다.</li>
	<li><code>B</code>와 그 뒤에 있는 <code>C</code>를 지운다.</li>
</ul>

<p>각 문자는 최대 한 번만 지울 수 있다.</p>

<p>예를 들어 <code>ABCBA</code>를 보자. 각 문자에 왼쪽부터 1번, 2번, 3번. . . 과 같이 번호를 붙이면 다음과 같이 시행할 수 있다.</p>

<ul>
	<li>1번 <code>A</code>와 2번 <code>B</code>를 지운다. 이 경우 시행의 횟수는 1번이고, 남은 문자열은 <code>CBA</code>이다. 어떤 두 문자를 골라도 시행의 조건을 만족시킬 수 없으므로, 더 이상 시행을 할 수 없다.</li>
	<li>1번 <code>A</code>와 4번 <code>B</code>를 지우고, 이어 2번 <code>B</code>와 3번 <code>C</code>를 지운다. 이 경우 시행의 횟수는 2번이고 남은 문자열은 <code>A</code>이다. 문자열에 남은 문자가 하나이므로, 더 이상 시행을 할 수 없다.</li>
</ul>

<p>이외에도 시행을 할 수 있는 여러 경우의 수가 있다.</p>

<p>시행을 할 수 있는 <strong>최대 횟수</strong>를 구해라.</p>

### 입력 

 <p>첫 번째 줄에 문자열 S가 주어진다.</p>

### 출력 

 <p>첫 번째 줄에 답을 출력한다.</p>