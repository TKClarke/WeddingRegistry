Assignment 7 - Wedding Planner

You need to write a program for a wedding planner. They wish to create a gift registry for each couple. They want the gifts broken down by the whether the gift giver is on the bride side or groom side. They also know that specific gifts (toasters, silverware, and stemware) tend to be repeated so they want those gifts listed and have the name of the gift giver under them. The repeating gifts are only the ones that have been told you by the client (toasters, silverware, and stemware) they do not want you to determine which gifts repeat, they are just looking for those specific three.

Assumptions:
There is only 1 registry for Bride and Groom
There is only 3 gifts told by client


Input:
familyside: Bride/Groom
guestname
gifttype

Calculations:
while loop (anotherGuest = yes)
groomAccum = + groomCount + guestName + gifttype
brideAccum = + brideCount + guestName + gifttype

switch (gifttype)
case toaster
case silverware
case stemware

anotherguest: yes/no?
if yes

end loop


Output:
groomAccum
brideAccum
toasterAccum
silverwareAccum
stemwareAccum