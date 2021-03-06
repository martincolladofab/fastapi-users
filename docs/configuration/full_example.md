# Full example

Here is a full working example with JWT authentication to help get you started.

!!! warning
    Notice that **SECRET** should be changed to a strong passphrase. 
    Insecure passwords may give attackers full access to your database.

``` py tab="SQLAlchemy"
{!./src/full_sqlalchemy.py!}
```

```py tab="MongoDB"
{!./src/full_mongodb.py!}
```

```py tab="Tortoise ORM"
{!./src/full_tortoise.py!}
```

## What now?

You're ready to go! Be sure to check the [Usage](../usage/routes.md) section to understand how yo work with **FastAPI Users**.
