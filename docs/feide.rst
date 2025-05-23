Jupyterhub access
===================


Creating Feide OpenIdP account:
-------------------------------

If you do not have a Feide account follow these instructions:

  - Go to `Feide OpenIdP <https://openidp.feide.no/>`_.

  - Click on `Register a new account <https://openidp.feide.no/simplesaml/module.php/selfregister/newUser.php>`_. Preferably provide the email you specified for the course.

  - You will receive an email from Feide OpenIdP \<noreply@sikt.no\>

  .. note::
     You might need to check your spam/junk folder

  - Click on the link in the email and proceed with further registration.

  - Now you have FEIDE **guest** account.

Joining eScience2025 Feide group:
---------------------------------


Once you created a FEIDE account (or if you already have one):
  - Go to `Innsyn Feide <https://innsyn.feide.no/login>`_.
  - Login in with FEIDE OpenID credentials
  - Go to `Personal information`
  - Uncollapse
  - Find your `Person's principal name at home organization` or `Mail`

    .. image:: ./img/feide_pi.png
       :height: 200

  - If you use OpenID, your personal page will look like, just send what is in the `Mail` and `User ID`:

    .. image:: ./img/openid.png
       :height: 200

  - Send email with this info to Matvey Debolskiy <matveyd@uio.no>.

  - You will shortly receive an invite to a feide group `eScience2025` (if you can't find it, look in spam)

  - Click on the link in the email. You will be suggested to login in into dataporten.
 
  - Login using your FEIDE account 

  .. note::

     For those with FEIDE guest accounts to login:
      - Click ``Can't find your user account?``
      - Choose ``Feide guest users``, you would be promted to the OpenIdP login page.

      .. image:: ./img/user_cant.png
          :width: 50 %
      .. image:: ./img/user_guest.png
          :width: 50 %

  - Accept policies and become member of **eScience2025** Feide group


Accessing Jupyterhub:
---------------------

Once you've become a memeber of **escience2025** Feide group you can use Jupyterhub for eScience2025 cource at `<https://escience2025.craas2.sigma2.no>`_.



  - Press ``Sing in with NIRD Apps Auth``.

  - Login with your Feide or Feide guest account. 

  .. collapse:: Feide Guests

     For those with FEIDE guest accounts:
      - Click ``Can't find your user account?``
      - Choose ``Feide guest users``, you would be promted to the OpenIdP login page.


.. warning:: **Test server access**

  Though `test sever <https://test-escience2025.craas2.sigma2.no>`_ is still reachable but will be shutdown soon.
  So if you have anything there, move it to escience2025 server. If you  need help ask **@mvdeoblskiy**.

