# Form with JQuery or Vue

This is a practical example for the Vue Talk for BolognaJs.
link for the Meetup event: [Meetup](https://www.meetup.com/Bologna-JS-Meetup/events/247514260/?gj=wcs1_e&rv=wcs1_e&_xtd=gatlbWFpbF9jbGlja9oAJDJjZGIwN2JjLWRmZDItNDU2YS1hYjVjLWM3OTdjZmNkZmIyZg&_af=event&_af_eid=247514260)

## Use Case

The canonical use case for jQuery has historically been submitting a form with an AJAX call, so we should take a look at that as well. Vue actually does not have a built-in thing like AJAX; it’s typical in Vue application to use something like Axios (a JavaScript library for making HTTP requests) to help with this task.

This example is a little more complicated than the rest. We’re going to do a few things here:

1. The button will appear grey before we start typing in our form, then it will receive an “active” class and turn blue;
2. When we submit the form, we’ll keep the page from loading;
3. When the form is submitted, we’ll show the response data on the page.
