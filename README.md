# T2
training
var_1 = list(range (-100, 101, 1))
print(var_1)
var_2 = list(range (250, -1, -2))
var_3 = list(range (101, 201, 2))
print(var_3)
a = 1
b = 4
def sum_of_range(a, b):
    total_sum = 0
    
    for num in range(a, b+1):
        total_sum += num
    
    return total_sum
result = sum_of_range(a, b)
print(result)
my_list = [11]
eleven_index = my_list.index(11)
print(eleven_index)
ten_count = my_list.count(10)
print(ten_count)
