# Number to Khmer Words Converter (បំលែងលេខទៅជាអក្សរខ្មែរ)

A simple yet powerful web application that converts numerical digits into Khmer word representations. This tool is particularly useful for official documents, financial reports, or educational materials where numbers need to be written in Khmer words.

## Features

- **Real-time Conversion**: Instantly converts numbers to Khmer words as you type
- **Large Number Support**: Handles numbers of any length, including:
  - Hundreds (រយ)
  - Thousands (ពាន់)
  - Millions (លាន)
  - Billions (ពាន់លាន)
  - Trillions (កោដិ)
  - And beyond (លានកោដិ, កោដិកោដិ)
- **Clean Interface**: Simple, user-friendly design
- **Mobile Responsive**: Works well on all device sizes
- **No Dependencies**: Pure HTML, CSS, and JavaScript implementation
- **Offline Support**: Works without internet connection

## Usage

1. Open `index.html` in any modern web browser
2. Type any number in the input field
3. See the Khmer word representation instantly below

## Examples

- 123 = មួយរយម្ភៃបី
- 1,000 = មួយពាន់
- 1,000,000 = មួយលាន
- 1,000,000,000 = ដប់រយលាន
- 1,000,000,000,000 = មួយកោដិ

## Technical Details

The converter uses a sophisticated algorithm to handle:
- Proper Khmer numerical scales
- Correct spacing between number groups
- Special cases for teen numbers
- Zero value handling
- Large number processing without JavaScript number precision limitations

## License

This project is open source and free to use for any purpose.

## Author

Created by Sokheng Hing
