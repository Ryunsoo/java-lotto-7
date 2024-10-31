# java-lotto-precourse

# 로또

---

## 기능 구현 목록

### 1. 로또 발매
- [x] 로또는 `6개의 숫자`를 가진다.
- [x] 로또가 가진 번호 목록은 null 일 수 없다.
- [x] 로또가 가질 수 있는 번호의 범위는 `1 ~ 45` 사이이다.
  - 번호는 null 일 수 없다.
  - 번호는 0 또는 음수일 수 없다.
- [x] 로또는 중복된 숫자를 가질 수 없다.

### 2. 당첨 번호 추첨
- [x] 추첨은 `6개의 당첨 번호`와 `1개의 보너스 번호`를 가진다.
- [x] 당첨 번호는 null 일 수 없다.
- [x] 보너스 번호의 범위는 `1 ~ 45` 사이이다.
  - 보너스 번호는 null 일 수 없다.
  - 보너스 번호는 0 또는 음수일 수 없다.
- [x] 보너스 번호는 6개의 숫자와 중복될 수 없다.

### 3. 로또 당첨 처리
- [ ] `6개`의 번호가 일치하면 `1등`을 반환한다.
- [ ] `5개`의 번호와 보너스 번호가 일치하면 `2등`을 반환한다.
- [ ] `5개`의 번호가 일치하면 `3등`을 반환한다.
- [ ] `4개`의 번호가 일치하면 `4등`을 반환한다.
- [ ] `3개`의 번호가 일치하면 `5등`을 반환한다.
- [ ] `2개` 이하로 번호가 일치하거나 일치하는 번호가 없으면 `낙첨`을 반환한다.

### 4. 로또 발매기
- [ ] 구입 금액은 null 이거나 0, 음수일 수 없다.
- [ ] 구입 금액은 `1,000원`으로 나누어 떨어져야 한다.
- [ ] 금액에 해당하는 만큼 로또를 생성하여 반환한다.

### 5. 총 당첨금액 계산
- [ ] 당첨 결과에 따라 당첨 금액을 계산하여 반환한다.

### 6. 수익률 계산
- [ ] 구입 금액과 당첨 금액으로 수익률을 계산하여 반환한다.

### 7. 입력 및 출력
- [ ] 구입금액을 입력받는다.
  - 입력이 잘 못된 경우 재입력을 진행한다.
- [ ] 구매한 로또를 오름차순으로 출력한다.
- [ ] 당첨 번호를 입력받는다.
    - 입력이 잘 못된 경우 재입력을 진행한다.
- [ ] 보너스 번호를 입력받는다.
    - 입력이 잘 못된 경우 재입력을 진행한다.
- [ ] 당첨 결과를 출력한다.
- [ ] 수익률을 소수점 둘째 자리에서 반올림하여 출력한다.
