# reel-reports
These report are designed around the parameters that Reel provides in it's print events. The list of events and parameters are as follows

Shipment
Used in Shipment List and Shipment Details Screens with the manual print button. Also used in the Pack and Ship auto events
```
SqlField = "Ship.Id", iReportParameter = "shipID"
SqlField = "Ship.Num", iReportParameter = "shipNum"
```

Picking
Used in Pick List and Pick Details Screens with the manual print button. Also used in the finish pick item auto event
```
Pick - 

SqlField = "Pick.Id", iReportParameter = "pickId"
SqlField = "Pick.Num", iReportParameter = "pickNum"
SqlField = "Pick.StatusId", iReportParameter = "pickStatusId"

Pick Item - 

SqlField = "PickItem.Id", iReportParameter = "pickItemId"
SqlField = "PickItem.OrderId", iReportParameter = "pickItemOrderId"
SqlField = "PickItem.OrderTypeID", iReportParameter = "pickItemOrderTypeID"
SqlField = "PickItem.SlotNumber", iReportParameter = "pickItemSlotNumber"

```

Product
Used with the manual Label button
```
SqlField = "Product.Num", iReportParameter = "productNum"
SqlField = "Product.Id", iReportParameter = "productId" 
SqlField = "Product.Upc", iReportParameter = "productUpc"
SqlField = "Part.Num", iReportParameter = "partNum"
```
