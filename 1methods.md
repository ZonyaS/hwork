print("Ввод объекта: ")
object = int(input())
for i in dir(object):
   if i[0]!="_":
      print(i) 
