import random
a = ['A few months ago', 'Yesterday', 'Last night', 'A few year ago','On 16th Feb']
b = ['Ravi', 'Rahul','Mohit', 'Ayush', 'Riya']
c = ['Bihar','Uttar Pradesh', 'Maharashtra', 'Rajasthan', 'Tamil nadu']
d = ['mall', 'university','a small shop', 'school', 'park']
e = ['made a lot of friends','Eats a burger', 'found a secret key', 'solved a mistery', 'wrote a book']
print(random.choice(a) + ', ' + random.choice(b) + ' that lived in ' + random.choice(c) + ', went to the ' + random.choice(d) + ' and ' + random.choice(e) + '.')
