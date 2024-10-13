### Version Control and Collaboration

---

It's essential to use a version control system for software developent and other documentation works.

Basic solution: Making copies

We need a systematic management system for version control and collaboration.

---

### Changes vs. Snapshots

---

#### Storing data as changes to the base version

변화된 부분만 저장

---

#### Storing data as snapshots

파일 전체를 저장

---

#### Local

혼자 버전을 컨트롤하기 위해 본인 컴퓨터에 저장

#### Centralized

Central VCS Server 중앙서버에 저장

#### Disrtibuted Version Control

중앙서버가 데이터를 가지며 Centralized와 달리 각각의 컴퓨터에서 버전 데이터 베이스를 가지는 차이가 있음. git은 이 방식을 채용함.

---

### Three states in GIt

---

Working Directory -> Staginf Area-> git directory(Repository)

commit을 하기전까지는 기록되지않음

---

Git config: First-time setup

---

#### Git configurations are stored in three levels:

1)System level: --system option. Affects all uses and repositories on the system(administrative)
file: /etc/gitconfig

2)Global (user) level: --global option. Affects all repositories of current user
file: ~/.config/git/config

3)Local level: --local option. Specific to the current repository
file: .git/gitconfig

Each level overrides values in the previous level: systtem ->global -> local
