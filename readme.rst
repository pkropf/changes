Home Page
=========

See http://pkropf.github.com/changes.

Background
==========

What is this thing? Excellent question. I'm not yet certain but I have
an idea.

Django is a wonderful, powerful framework for web developement. Works
great. For many business applications, there is a general need to
create forms that staff fill out for various business
processes. A couple of quick examples would be:

 * Purchase order form
 * Network / IT account creation

In both cases, the forms are submitted and other things need to
happen. In the case of the PO, it would most likely need approval,
marked as ordered, marked as received, and marked as paid. In some
cases, there could also be a request back to the originator asking for
more details or clairification. In the case of the IT account form, it
needs to be marked ask created.

In addition, any changes made to the data should be logged so that
there's an audit history for the particular form instance.

It's basically a workflow system added to Django forms.
