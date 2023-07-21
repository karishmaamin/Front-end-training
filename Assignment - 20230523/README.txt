Why ID has to be Unique?
ID are used to choose particular element in webpage. And to differentiate/choose one element with the rest of the elements
we use ID. We will run into a problem accessing element in Javascript because js will return the first element with same ID.
////////////////////////////////////////////////

what happens if there are multiple id's on the webpage
the specified styles to all elements given the same id.
Ids contain only first div element. So even if there are multiple elements with the same id,
the document object will return only first match mainly at the time of redirecting to section of the page.
It's possible to have duplicate ids.
////////////////////////////////////////////

If styles applied to multiple ID what will happen?
Most browsers will apply the specified styles to all elements given the same id.
However, this is considered bad practice.
/////////////////////////////////////////////

What happens if I target ID in Javascript?
If used multiple elements with the same ID, we will run into problems when using JavaScript to
access those elements.
For example, when used document.getElementById('duplicateId') ,
we will get the one element(first element) instead of two.