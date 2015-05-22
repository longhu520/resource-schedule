# Resource Scheduler #

## Overview ##

Java Swing GUI component for scheduling resource usage.  This is not really intended to be used as an all-purpose calendar.  For something like that you are better off going to [http://www.migcalendar.com/](http://www.migcalendar.com/).

This component would be better used to, for example, schedule a service for a car.  If the auto dealership has four mechanics then this would provide a way to schedule appointments which each mechanic.  In this example each mechanic would be a resource and the appointments could be of varying lengths.

## Design ##

The component is being developed as a standard M/VC component where you can provide the component a model which can be queried for appointments and resources available on a given day.

## Status ##

This component is still in the very early stages of development.
<br />
<img src='http://resource-scheduler.thirdnf.com/screenshots/ResourceScheduler_0_2.png'>