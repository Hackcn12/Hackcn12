11
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
# track location and time zone using the phone number
import phonenumbers
from phonenumbers import timezone
from phonenumbers import geocoder
from phonenumbers import carrier
 
number = input("+966500367467")
 
# Parsing String to the Phone number
phoneNumber = phonenumbers.parse(+966500367467)
 
# printing the timezone using the timezone module
timeZone = timezone.time_zones_for_number(phoneNumber)
print("timezone : "+str(timeZone))
 
# printing the geolocation of the given number using the geocoder module
geolocation = geocoder.description_for_number(phoneNumber,"en")
print("location : "+geolocation)
 
# printing the service provider name using the carrier module
service = carrier.name_for_number(phoneNumber,"en")
print("service provider : "+service)
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
# track location and time zone using the phone number
import phonenumbers
from phonenumbers import timezone
from phonenumbers import geocoder
from phonenumbers import carrier
 
number = input("Enter the phone number with country code : ")
 
# Parsing String to the Phone number
phoneNumber = phonenumbers.parse(number)
 
# printing the timezone using the timezone module
timeZone = timezone.time_zones_for_number(phoneNumber)
print("timezone : "+str(timeZone))
 
# printing the geolocation of the given number using the geocoder module
geolocation = geocoder.description_for_number(phoneNumber,"en")
print("location : "+geolocation)
 
# printing the service provider name using the carrier module
service = carrier.name_for_number(+966500367467,"ar")
print("service provider : "+service)- 👋 Hi, I’m @Hackcn12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Hackcn12/Hackcn12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
