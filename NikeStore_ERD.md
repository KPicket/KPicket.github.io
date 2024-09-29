'''mermaid 
erDiagram
CUSTOMER || --o{PRODUCT: Chooses
CUSTOMER { 
    string Name
    string Email
}
PRODUCT||--o{SALE: Sold 
PRODUCT {
    string Name
    string Size
    
}
SALE||--o{INVENTORY:Changes
SALE {
    string Cost
    string PurchaseDate

}
PRODUCT||--o{INVENTORY:Count
INVENTORY {
    string TotalRemaining
    string TotalSold
} 
'''
    

