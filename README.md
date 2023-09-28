# mediaprata

def mediaPrata(n):
  result = 0
  if n > 12:
   return result 
  else:
    result = (n + ((4 + n**2)**0.5)) / 2
    print(f"Variação da média {n} = {result}")
    mediaPrata(n + 1)

mediaPrata(0)
