# if 이후 elif를 사용해서 연속적으로 조건을 걸어줍니다. 
# 좌표를 dot이라는 매개변수로 사이트에서 먼저 제공합니다. 인덱스 값으로 호출하면 되므로, 따로 매개변수를 선언하지 않습니다.
# else 이후는 제 4분면에 해당하는 한 가지의 경우의 수 밖에 없으므로, 따로 구분해주지 않습니다.

def solution(dot):
    if (dot[0] > 0) & (dot[1] > 0):  
        answer = 1
    elif (dot[0] < 0) & (dot[1] > 0):
        answer = 2
    elif (dot[0] < 0) & (dot[1] < 0):
        answer = 3
    else:
        answer = 4
    return answer 
