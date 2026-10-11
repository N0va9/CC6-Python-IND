SALES

SalesOrderLineKey        ->
ResellerKey                    ->
CustomerKey                 ->
ProductKey                    ->
OrderDateKey                ->
DueDateKey                   ->
ShipDateKey                  ->
SalesTerritoryKey           ->
Order Quantity              -> Nombre d'unités du produit vendues sur la ligne de commande
Unit Price                       -> Prix de vente d'une seule unité du produit
Extended Amount          -> Montant brut de la ligne de vente avant remise (OrderQuantity x UnitPrice
Unit Price Discount Pct  -> Taux de remise appliqué au prix unitaire (en %)
Product Standard Cost  -> Coût standard unitaire du produit (coût de revient)
Total Product Cost         -> Coût total du produit pour la ligne (OrderQuantity x ProductStandardCost
Sales Amount                -> CA net de la ligne après remise (OrderQuantity x UnitPrice x (1 - UnitPriceDiscountPct)
