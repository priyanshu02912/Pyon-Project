# Python-Project
#Python project for selecting a random story
ocassion=['On the occasion of New Year','On the occasion of Christmas','On 26th january 2023']

member=['Nitish and his friends','Aditya and his friends','Priyanshu and his friends']

trip=['will go for Shimla trip.','will go for Rajgir trip.','will go for Kashmir trip.']

staying=['They will staying for two days, one night at there','They will staying for three days, two night at there','They will staying for two days, two night at there']

happening=['vists all famous palces', 'enjoy the trip']

activity=[ 'with his friends and try to interact with local people.','and one of them, make a small blog of trip to show how the culture is different from us.','and explore new culture and what are the difficulites they are facing in day to day life.','and explore how their life is different from us.']


print(random.choice(ocassion)+','' '+random.choice(member)+' '+random.choice(trip)+' '+random.choice(staying)+','' '+random.choice(happening)+' '+random.choice(activity))
