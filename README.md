# MidtermQuestion6
Problem 6

def max_val(t):
def openItem(term):
newList = []
for item in term:
  if type(item) == int:
    newList.append(item)
    
  else:
    newList += openItem(item)
  return newList
  
  sortingList = openItems(t)
  maximum = sortingList[0]
  
  for item in sortingList:
  if maximum < item:
  maximum = item
  return maximum
  
  print(max_val((5, (1,2), [[1],[2]]))
  print(max_val((5, (1,2), [[1],[9]]))
