import random
import time

game_nums = 1000000
# game_count = 0
gate_nums = 3
win = 0

def game(i):
    foods = ['A'] * gate_nums
    foods[random.randint(0,gate_nums-1)] = 'B'
    food = random.choice(foods)
    global win 
    # global game_count
    # game_count += 1
    if food == 'A':
        win += 1
        # print(str(game_count)+'次win')
    else:
        pass


for i in range(game_nums):
    t = game(i)


print(win/game_nums)
