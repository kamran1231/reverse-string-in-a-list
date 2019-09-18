# reverse-string-in-a-list

def reverse_list(l):
    element = []
    for i in l:
       element.append(i[::-1])
    return element


l = ['kamran','khan']
print(reverse_list(l))
