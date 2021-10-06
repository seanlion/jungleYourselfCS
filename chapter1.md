## Chapter 1 - OS & Computer System

### Introduction

이 챕터는 Stanford의 유명 강의 CS110를 들으며, OS 공부에 필요한 지식을 컴퓨터 시스템 강의에서 나온 개념으로 이해하는 챕터입니다.

CS 110은 주로 프로세스, 스레드, 동시성, 파일 시스템 등에 대해 다룹니다. OS를 제대로 다루는 과목은 CS 140이지만 CS 140에 대한 퍼블릭한 자료를 구하기 힘들고, 이 수업으로도 OS에서 쓰이는 기본적인 지식을 충족할 수 있기 때문에 110을 채택하게 되었습니다.

첫 강의부터 순서대로 들어도 상관은 없지만, 운영체제 개발 위주로 듣고 싶다면 아래의 순서만 따라가도 좋습니다. 

1.스레드, 프로세스 : 9,10,11,12,13,8강

2.시스템 콜 : 4,5강

3.파일 시스템 : 2,3강

### Topics

- **Linux Filesystems**
- **Multiprocessing and Exceptional Control Flow**
- **Threading and Concurrency**
- **Networking and Distributed Computing**

### Resources

강의 자료는 2019 Spring 강의입니다만, 최신 학기 강의와 내용이 크게 다르지 않습니다. (최신 자료를 원하시는 분들은 직접 찾아서 들어보세요 🙂)

- [강의 비디오](https://www.youtube.com/playlist?list=PLai-xIlqf4JmTNR9aPCwIAOySs1GOm8sQ)
- [강의 노트](https://web.stanford.edu/class/archive/cs/cs110/cs110.1204/static/lectures/)

### Checklist

- [ ] 스레드와 프로세스 차이를 설명해볼 수 있나요?
- [ ] 데드락과 경쟁상태가 무엇인지 알고 있나요?
- [ ] 공유 자원 제어를 위한 개념(뮤텍스, 락, 세마포어)을 이해하고 있나요?
- [ ] rdi, rsi, rax 같은 개념을 이해하고 있나요?
- [ ] 인터럽트 핸틀러가 하는 일을 알고 있나요?
- [ ] 리눅스 파일 permission 체계는 무엇인가요?
- [ ] 파일 시스템에서 섹터와 블록은 무엇인가요?
- [ ] inode 개념에 대해 설명해볼 수 있나요?
- [ ] 직접 주소, 간접 주소 개념에 대해 알고 있나요?

### Advanced

- [Condition Variable이란](https://modoocode.com/270)
- [CS 140 강의노트](https://web.stanford.edu/~ouster/cgi-bin/cs140-spring20/lectures.php)