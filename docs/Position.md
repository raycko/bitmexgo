# Position

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | **int** |  | [default to null]
**Symbol** | **string** |  | [default to null]
**Currency** | **string** |  | [default to null]
**Underlying** | **string** |  | [optional] [default to null]
**QuoteCurrency** | **string** |  | [optional] [default to null]
**Commission** | **float64** |  | [optional] [default to 0.0]
**InitMarginReq** | **float64** |  | [optional] [default to 0.0]
**MaintMarginReq** | **float64** |  | [optional] [default to 0.0]
**RiskLimit** | **int** |  | [optional] [default to null]
**Leverage** | **float64** |  | [optional] [default to 0.0]
**CrossMargin** | **bool** |  | [optional] [default to null]
**DeleveragePercentile** | **float64** |  | [optional] [default to 0.0]
**RebalancedPnl** | **int** |  | [optional] [default to null]
**PrevRealisedPnl** | **int** |  | [optional] [default to null]
**PrevUnrealisedPnl** | **int** |  | [optional] [default to null]
**PrevClosePrice** | **float64** |  | [optional] [default to 0.0]
**OpeningTimestamp** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**OpeningQty** | **int** |  | [optional] [default to null]
**OpeningCost** | **int** |  | [optional] [default to null]
**OpeningComm** | **int** |  | [optional] [default to null]
**OpenOrderBuyQty** | **int** |  | [optional] [default to null]
**OpenOrderBuyCost** | **int** |  | [optional] [default to null]
**OpenOrderBuyPremium** | **int** |  | [optional] [default to null]
**OpenOrderSellQty** | **int** |  | [optional] [default to null]
**OpenOrderSellCost** | **int** |  | [optional] [default to null]
**OpenOrderSellPremium** | **int** |  | [optional] [default to null]
**ExecBuyQty** | **int** |  | [optional] [default to null]
**ExecBuyCost** | **int** |  | [optional] [default to null]
**ExecSellQty** | **int** |  | [optional] [default to null]
**ExecSellCost** | **int** |  | [optional] [default to null]
**ExecQty** | **int** |  | [optional] [default to null]
**ExecCost** | **int** |  | [optional] [default to null]
**ExecComm** | **int** |  | [optional] [default to null]
**CurrentTimestamp** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**CurrentQty** | **int** |  | [optional] [default to null]
**CurrentCost** | **int** |  | [optional] [default to null]
**CurrentComm** | **int** |  | [optional] [default to null]
**RealisedCost** | **int** |  | [optional] [default to null]
**UnrealisedCost** | **int** |  | [optional] [default to null]
**GrossOpenCost** | **int** |  | [optional] [default to null]
**GrossOpenPremium** | **int** |  | [optional] [default to null]
**GrossExecCost** | **int** |  | [optional] [default to null]
**IsOpen** | **bool** |  | [optional] [default to null]
**MarkPrice** | **float64** |  | [optional] [default to 0.0]
**MarkValue** | **int** |  | [optional] [default to null]
**RiskValue** | **int** |  | [optional] [default to null]
**HomeNotional** | **float64** |  | [optional] [default to 0.0]
**ForeignNotional** | **float64** |  | [optional] [default to 0.0]
**PosState** | **string** |  | [optional] [default to null]
**PosCost** | **int** |  | [optional] [default to null]
**PosCost2** | **int** |  | [optional] [default to null]
**PosCross** | **int** |  | [optional] [default to null]
**PosInit** | **int** |  | [optional] [default to null]
**PosComm** | **int** |  | [optional] [default to null]
**PosLoss** | **int** |  | [optional] [default to null]
**PosMargin** | **int** |  | [optional] [default to null]
**PosMaint** | **int** |  | [optional] [default to null]
**PosAllowance** | **int** |  | [optional] [default to null]
**TaxableMargin** | **int** |  | [optional] [default to null]
**InitMargin** | **int** |  | [optional] [default to null]
**MaintMargin** | **int** |  | [optional] [default to null]
**SessionMargin** | **int** |  | [optional] [default to null]
**TargetExcessMargin** | **int** |  | [optional] [default to null]
**VarMargin** | **int** |  | [optional] [default to null]
**RealisedGrossPnl** | **int** |  | [optional] [default to null]
**RealisedTax** | **int** |  | [optional] [default to null]
**RealisedPnl** | **int** |  | [optional] [default to null]
**UnrealisedGrossPnl** | **int** |  | [optional] [default to null]
**LongBankrupt** | **int** |  | [optional] [default to null]
**ShortBankrupt** | **int** |  | [optional] [default to null]
**TaxBase** | **int** |  | [optional] [default to null]
**IndicativeTaxRate** | **float64** |  | [optional] [default to 0.0]
**IndicativeTax** | **int** |  | [optional] [default to null]
**UnrealisedTax** | **int** |  | [optional] [default to null]
**UnrealisedPnl** | **int** |  | [optional] [default to null]
**UnrealisedPnlPcnt** | **float64** |  | [optional] [default to 0.0]
**UnrealisedRoePcnt** | **float64** |  | [optional] [default to 0.0]
**SimpleQty** | **float64** |  | [optional] [default to 0.0]
**SimpleCost** | **float64** |  | [optional] [default to 0.0]
**SimpleValue** | **float64** |  | [optional] [default to 0.0]
**SimplePnl** | **float64** |  | [optional] [default to 0.0]
**SimplePnlPcnt** | **float64** |  | [optional] [default to 0.0]
**AvgCostPrice** | **float64** |  | [optional] [default to 0.0]
**AvgEntryPrice** | **float64** |  | [optional] [default to 0.0]
**BreakEvenPrice** | **float64** |  | [optional] [default to 0.0]
**MarginCallPrice** | **float64** |  | [optional] [default to 0.0]
**LiquidationPrice** | **float64** |  | [optional] [default to 0.0]
**BankruptPrice** | **float64** |  | [optional] [default to 0.0]
**Timestamp** | [**time.Time**](time.Time.md) |  | [optional] [default to null]
**LastPrice** | **float64** |  | [optional] [default to 0.0]
**LastValue** | **int** |  | [optional] [default to null]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


