# Oh-so-gi

*  git for uploading data about open_source_project
*  operating project
*  it is part of university class assignment
*  I am in SS university AI convergence

## LAB 1-1
### ***Selection sorting(최소값 중심 정리)***
def selectionSort(list):
  for i in range(len(list)):
    min_idx=i
    for j in range(i+1,len(list)):
      if list[min_idx] > list[j]:
        min_idx=j
    list[i], list[min_idx] = list[min_idx],list[i]
list = [64, 25, 12, 22 ,11]
print("Orginal list =%s"%list)
selectionSort(list)
print("Sorted list by Selection method")
print(list)

## LAB 1-2
### ***Bubble sorting (최소값 중심 정리)***
def bubbleSort(list):
  n=len(list)
  for i in range(n):
    for j in range(0,n-i-1):
      if list[j]>list[j+1]:
        list[j],list[j+1]=list[j+1],list[j]
list=[64,34,25,12,22,11,90]
print("Orginal list=%s"%list)
bubbleSort(list)
print("Sorted list by Bubble method")
print(list)
