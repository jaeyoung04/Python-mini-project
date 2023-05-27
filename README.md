# Python-mini-project
temp1 = int(input("첫번째 값을 입력하세요."))
python = input("사칙연산을 입력하세요(더하기, 빼기, 곱하기, 나누기)")
temp2 = int(input("두번째 값을 입력하세요."))

if python == "더하기":
    n = temp1 + temp2

elif python == "빼기":
    n = temp1 - temp2

elif python == "곱하기":
    n = temp1 * temp2

elif python == "나누기":
    n = temp1 / temp2

print(n)
