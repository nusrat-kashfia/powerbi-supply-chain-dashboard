# DAX Measures

## Total Revenue

```DAX
Total Revenue =
SUM(Sales[Revenue])
```

Description:

Calculates total revenue.

---

## Inventory Value

```DAX
Inventory Value =
SUMX(
    Inventory,
    Inventory[Stock On Hand] *
    RELATED(Products[Unit Cost])
)
```

Description:

Calculates the total value of current inventory.

---

## Average Lead Time

...

---

## Purchase Cost

...

---

## Revenue Growth %

...