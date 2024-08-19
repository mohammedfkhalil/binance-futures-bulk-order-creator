# Binance Futures Bulk Order Creator
![binance_futures_bulk_order_creator](https://github.com/user-attachments/assets/47660686-f5b7-4b99-a870-ddee6d4081a1)

This is a web-based application that allows users to create multiple orders on Binance Futures simultaneously. It provides a user-friendly interface for inputting API credentials, selecting trading pairs, specifying price ranges, and creating either long or short orders in bulk.

## Features

- Real-time symbol and price data fetching
- Account balance and open positions display
- Dynamic order size calculation based on account balance or open position
- Support for both limit and stop-limit orders
- Reduce-only order option
- Responsive design for various screen sizes

## Usage

1. Open the HTML file in a web browser.
2. Enter your Binance Futures API key and secret.
3. Select a trading pair from the dropdown menu.
4. Set the lower and upper price limits for your orders.
5. Specify the number of orders you want to create.
6. Adjust the total amount using the slider or by selecting an open position.
7. Choose whether to use stop-limit orders and/or reduce-only orders.
8. Click "Create Long Orders" or "Create Short Orders" to submit the bulk orders.

## Security Note

This application requires a valid Binance Futures API key and secret to function properly. Never share your API credentials with others, and use this tool at your own risk. Ensure you understand the implications of bulk order creation in cryptocurrency trading.

## Disclaimer

Trading cryptocurrencies carries a high level of risk and may not be suitable for all investors. The high degree of leverage can work against you as well as for you. Before deciding to trade cryptocurrencies, you should carefully consider your investment objectives, level of experience, and risk appetite. The possibility exists that you could sustain a loss of some or all of your initial investment and therefore you should not invest money that you cannot afford to lose.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/yourusername/binance-futures-bulk-order-creator/issues) if you want to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by Mohammed Khalil
- GitHub: [https://github.com/mohammedfkhalil](https://github.com/mohammedfkhalil)

## Acknowledgments

- Binance for providing the Futures API
- CryptoJS library for HMAC-SHA256 signature generation
