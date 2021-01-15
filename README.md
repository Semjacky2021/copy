# 相向双指针（patition in quicksort）
def patition(self, A, Start, end):
    if start >= end:
        return
    left, right = start, end
    # key point 1: pivot is the value, not the index
    pivot = A [(start + end) // 2]；
    # key point 2； every time you compare left & right, is should be 
    # left <= right not left < right
    
