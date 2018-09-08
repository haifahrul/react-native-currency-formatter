# react-native-currency-formatter 
## Javascript - React Native
### Currency Formatter Rupiah Indonesia and US Dollar
-------------------------

 This is the JavaScript widget used only IDR and USD, you can change according to your needs.
 If you use for IDR, the value or price is automatically round a number upward to its nearest integer:

 This widget has implemented in React Native version 0.53.0.
 
 

# HOW TO USE
#### Configuration
> Config the currency
```
const currencyCode = 'IDR '; // IDR or USD
const currencyPosition = 'left' // left or right
const maxFractionDigits = 2;
const decimalSeparator = ',';
const thousandSeparator = '.'; 
```

#### Usage
- Create file CurrencyFormatter in your folder project.
- import in your components
`import CurrencyFormatter from '_YOUR_ROOT_FILE/CurrencyFormatter';`
- call the formatter
`${ CurrencyFormatter(value_of_price) }`  

# EXAMPLE
##### For IDR (Indonesian Rupiah)
- `${ CurrencyFormatter(1234511) }` 
- Result `IDR 1.234.511`

##### For US Dollar

- `${ CurrencyFormatter(1234511.47) }`
- Result `IDR 1,234,511.47`
