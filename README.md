Currency convertor Mexico Canada and USA 
May 13 at 8:15 PM
enum Currency
case cad
case mxn

let usToCad = 1.33
let usToMxn = 19.70
let Currency = Currency.cad
func convert(_dollars: Double) -> Double
switch Currency
case .cad:
    print()
    usToCad * dollars
    default:
    usToMxn * dollars

    return dollars

    func convert(amountString: String)
    guard let amount = Double(amountString) else { return nil }
    let convertCurrency = convert(amount)
   
    return String(convertCurrency)
    
convert(amountString: "57.0")
Currency = .mxn
convert(amountString: "57.0")
