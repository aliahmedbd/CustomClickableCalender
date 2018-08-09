# Custom Clickable Calender
Sometimes we need to develop our custom calendar where date cells have to create our-self. So that I develop a calendar where date fields are created using GidView. Where basic calendar with range selector implemented. Anyone can modify this as well as can add extra functionalities. This calendar is fully customizable.You also can add events using EventObjects class. 

## Date Range
Clicking date cells user can set date range like start date to end date. Some logics are there which are
- First selected item will be the start date.
- The second one will be the end date.
- A user can increase or decrease the Start date and End date.

## Custom Events
```java
   //Custom Events
   EventObjects eventObjects = new EventObjects(1, "Birth", new Date());
   eventObjects.setColor(R.color.colorPrimary);
   List<EventObjects> mEvents = new ArrayList<>();
   mEvents.add(eventObjects);
```
<img src="https://github.com/aliahmedbd/CustomClickableCalender/blob/master/Screenshot_20180809-174741.png" width="250" alt="Screenshot 1"/>


## Screenshots 
<img src="https://github.com/aliahmedbd/CustomClickableCalender/blob/master/Screenshot_20180809-163417.png" width="250" alt="Screenshot 1"/>
<img src="https://github.com/aliahmedbd/CustomClickableCalender/blob/master/Screenshot_20180809-163422.png" width="250" alt="Screenshot 2"/>
<img src="https://github.com/aliahmedbd/CustomClickableCalender/blob/master/Screenshot_20180809-163432.png" width="250" alt="Screenshot 3"/>


