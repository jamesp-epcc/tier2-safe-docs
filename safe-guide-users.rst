SAFE for Individual Users
=========================

`SAFE <https://www.archer.ac.uk/cirrus/>`__ is an online user
service management system. Through SAFE, individual users can request
machine accounts, reset passwords, see available resources and track
their usage. All users must be registered on SAFE before they can apply
for an account on the Cirrus facility.

SAFE: Registering, logging in, passwords
----------------------------------------

How to register on SAFE
~~~~~~~~~~~~~~~~~~~~~~~

If you are already registered on the ARCHER or Tier-2 SAFE the same login
credentials will also work on the Cirrus SAFE and you don't need to re-register. 

#. Go to the SAFE `New User Signup
   Form <https://www.archer.ac.uk/cirrus/signup.jsp>`__
#. Fill in your personal details. You can come back later and change
   them if you wish
#. Click "Submit"
#. You are now registered. A single use login link will be emailed to the
   email address you provided. You can use this link to login and set
   your password.

At this point your account is registered on the SAFE but you do not
have a user account on the Cirrus system. To obtain a machine account on
Cirrus please follow the instructions below.

How to login to SAFE and Overview of Main Page
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Go to the SAFE <https://www.archer.ac.uk/cirrus/>`__

#. Type in the email address you have registered with
#. Type in your SAFE password
#. Click "Login"
#. You are now on the Main Page and here you can see Menus along the top
   which give access to SAFE functionality

How to register an Institutional Login
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Once you have a SAFE account you can link it to your normal university
Institutional web-login. 

`Go to the SAFE <https://www.archer.ac.uk/cirrus/>`__

#. Select "Register Institutional ID" from the "Your details" menu
#. Select your home institution
#. Login to your home institution if redirected to their login page.

This will allow you to use the "Institutional Login" button when logging in
to the SAFE.


How to change your personal details on SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Your details* and select *Update personal details*
#. Make the changes you wish
#. Click *Commit Update* to save the changes
#. Go back to *Your details* and you will see the revised information

Do not forget the last step, or nothing will happen. Note that your
postal address does not automatically include the name of your
department and institution; if you want these in your postal address,
you must type them again.

How to change your email address on SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Your details* and select *Update email*
#. Enter the new email address and click *Request*

A verification email will then be sent to the new email address. This
email contains a link which you must use to verify your new address. On
acknowledging your new address the change will be committed and you must
use the new email address when logging into SAFE

How to change your SAFE password
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Your details* and select *Change SAFE password*
#. Fill in the boxes and click *Change*

How to reset your SAFE password
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Enter your email address
#. Click *Email*
#. SAFE will mail a one time login link to your email address

SAFE will only mail to email addresses it already knows.

Of course, anyone could go to SAFE, type your email address and request
a login link by clicking "Email". If that happens you will receive an
email message out of the blue with the login link. In this case you
should certainly use the link to login and set a new password.

How to add an SSH key to your SAFE account
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Some facilities may require you to register an SSH key in the SAFE
before you can request an account on the system. To do this you will
require a SSH key pair. You upload the *public part* of the key pair
to your SAFE account as follows:

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Your details* and select *Update personal details*
#. Either copy and paste the public part of your SSH key into the
   "SSH Public key" box or use the button to select the public key file 
   on your computer.
#. Click *Commit Update* to save the changes
#. Go back to *Your details* and you will see the revised information

Do not forget the last step, or nothing will happen.

How to request access to a Package Group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Some software which is installed on Cirrus can only be accessed once the user's
licence has been confirmed.

For some of these packages, such as VASP, you can request access via SAFE

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Login accounts* and select the account which requires access to the package
#. Click *New Package Group Request*
#. Select the package from the list of available packages and click *Select Package Group*
#. Fill in as much information as possible about your licence, at the very least, the information requested at the top of the screen such as the licence holder's name and contact details.
#. If you are covered by the license because the licence holder is your supervisor, for example, please state this.
#. Click *Submit*

Your request will then be processed by the appropriate support team who will confirm your license with the approriate authority before enabling your access to the package. This can take several days but you will be advised once this has been done.

Cirrus Facility: Accounts, passwords
------------------------------------

How to request a system account on the Cirrus facility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The minimum you require to create an account on Cirrus is
a SAFE account and a *Project Code*. You should sign up for a SAFE 
account as described above and Your project's PI or Project
Manager should be able to supply you with the project code.

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Login accounts* and select *Request login account*
#. Choose the project you want the account for in the "Choose Project
   for Machine Account" box.
#. Choose the system you want the account on by selecting from the
   available systems.
#. Enter the username you would prefer to use on the system
   Every username must be unique, and you must create a new system
   account with a unique username for each project you work on.

Now you have to wait for your PI or project manager to accept your
request to register. When this has happened, the systems team are
prompted to create your account on the service machine. Once this has
been done, you will be sent an email. You can then pick up your
password for the service machine from your SAFE account.

How to reset a password on your machine account
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you still remember your current machine account password, you can
simply log in to Cirrus as normal and then use the passwd command

::

    passwd

You will then be prompted to enter your current password, and then your
new password twice.

If you have forgotten your current password, or it has expired, then you
can ask for it to be reset:

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Login accounts* and select the account you need the
   new password for
#. Click *username* which displays details of this service machine
   account.
#. Click *New Login Account Passwd*

Now your password will be changed. When this has been done,
you will be informed by email; this means that you can come back to SAFE
and pick up your new password.

How can I pick up my password for a Cirrus system account?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Wait till you receive the email with your details. Then:

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Login accounts* and you will see your Cirrus accounts
   listed. Click on the appropriate account.
#. This will display details of your account. Click *View Login Account
   Password* You will need to enter in your SAFE password and then click
   *view*, and you will see your password to the service machine

This password is generated randomly by the software. It's best to
copy-and-paste it across when you log in to the facility.

After you login, you will be prompted to change it. You should paste in
the password retreived from SAFE again, and then you will be prompted to
type in your new, easy-to-remember password, twice. 

Note that when you change your password on the facility in this
way, this is not reflected on the SAFE.

User Mailing Options
--------------------

How to view user mailings
~~~~~~~~~~~~~~~~~~~~~~~~~

| All mailings are archived and can be viewed in
  `SAFE <https://www.archer.ac.uk/cirrus/>`__.
| Please login to SAFE and go to the section *View user
  mailings*. Press the *View* button to access the mailings.

How to get added to, or removed from the email mailing list?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Click on the Menu *Your details* click *Update personal details* find
   *Opt out of user emails* field and click it
#. Click *Commit Update*

Do not forget the last step, or nothing will happen.

**Note:** Regardless of whether you are subscribed to the
mailing list, you can still view ALL user mailings which have been sent,
in SAFE.


Tracking Resource Usage
-----------------------

How to check how much time and space are available to you
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__
and Go to the Menu *Login accounts*, select
the *username* which you wish to see details for. You will then see the
information for this account. You will see the quotas for the disk space
(if the project group/system is using these) and how much is in use.

The budget values displayed are updated every morning, and the values
shown for disk use are updated four times a day. For this reason, all
these values may not be completely up-to-date. If there is a lot of
activity in your project, the numbers shown could be significantly
different from from the current ones.

How to review the use you have made of the service, or the activity of the service as a whole
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <https://www.archer.ac.uk/cirrus/>`__. Then:

#. Go to the Menu *Service information* and select *Report Generator*
#. Select the report you wish to run
#. Complete the required information in the form: this will usually
   consist of at least a date range to analyse and may have other
   options depending on the report you are running.
#. Click the icon for the output format you would like to generate.
   If you select preview you will get a report in the web browser 
   with buttons to use to output the analysis in other formats.

If you are a PI or Project Manager, you will have access to additional
reports to generate information on whole projects or groups as well as
your own usage and the usage of the Cirrus facility as a whole.

