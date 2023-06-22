# Eagle_Twins
오늘할일 별로 피라미드 만들기 서로 코드 리뷰
https://discord.gg/9MWXxddw

def draw_pyramid(height):
    for i in range(height):
        print('*' * (i + 1))

# 피라미드의 높이를 입력받습니다.
height = int(input("피라미드의 높이를 입력하세요: "))

# 피라미드를 그립니다.
draw_pyramid(height)

output = ""
for i in range(1, 10):
    for j in range(0, i):
        output += "*"
    output += "\n"

print(output)
