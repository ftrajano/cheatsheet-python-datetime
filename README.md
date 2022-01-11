# cheatsheet-python-datetime
A cheatsheet for the python's datetime library


## from datetime import date
for creating a datetime object we can use de method **date** as below:
```python
date1 = date(1992,12,1)
date2 = date(1992,11,1)
```

The datetime object has a lot of useful properties:
* datetime.date.weekday()
* datetime.date.year
* datetime.date.month
* datetime.date.day


## Math with dates
Like numbers, we can operate with dates but de result of this operation is a timedelta and we need to call the atribute days to get the difference.
delta = date1-date2
print(delta.days) -> 30

