
Django Mailgun Example
==============
This is so simple mailgun python script for your django project.

You are put mailgun.py to into your project.
 
That's it. You can use its.

example html mail:

context = Context({'username': 'cemkiy', 'email': 'se.cemkiy@gmail.com'})

mailgun_operator = mailgun()

mailgun_operator.send_mail_with_html('se.cemkiy@gmail.com', 'show_username.html', context, 'show username')


example text mail:

mailgun_operator = mailgun()

mailgun_operator.send_mail('se.cemkiy@gmail.com', 'your username cemkiy', 'show username')