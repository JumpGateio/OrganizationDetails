# Things not covered in psr-2

- You SHOULD ALWAYS align your variables.

# Routes

## Prefixes

Prefixes should always be singualr.  This solves the confusion of some being plural and some being singular.  By using singular 
you avoid the problem of some being just an `s` and some being `ies`.

## Route Names
These should be singular for the area.  For example, if your service is called `Announcing` your route names should all begin 
with `announcement`.

If your route is in a context other than `default`, add the prefix as the first part of the route name.  For example, if your 
in the admin context your route name should begin with `admin.`.
