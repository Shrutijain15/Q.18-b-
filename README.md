# Q.18-b-
def convert_to_octal(num)
  if num>0:
       convert_to_octal(num // 8)
       print(num % 8, end='')
  convert_to_octal(33)
