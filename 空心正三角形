# -1
空心正三角形
這裡是一個 Python 函數，可以輸出邊長為 n 的空心正三角形。

程式碼

def hollow_triangle(n):
    if n < 1:
        return
    
    for i in range(n):
        if i == 0:
            print(" " * (n - 1) + "*")
        elif i < n - 1:
            print(" " * (n - i - 1) + "*" + " " * (2 * i - 1) + "*")
        else:
            print("*" * (2 * n - 1))

# 測試
hollow_triangle(3)

輸入 3 的輸出結果

  *
 * *
*****
