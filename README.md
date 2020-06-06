# Convert HTML content to PDF 

This program is specifically for converting AWS FAQ pages to PDF for offline access and other note taking purposes. 

Python webscraping program to convert html content to PDF.

Enter AWS Service name or the slug in <https://aws.amazon.com/[SLUG]/faqs/> to download the corresponding FAQ as PDF. 

## Usage

```bash
>> pipenv shell
>> pipenv install
>> chmod +x convert-faq-to-pdf
>> ./convert-faq-to-pdf [SLUG]
```

## Example

```bash
>> ./convert-faq-to-pdf dynamodb
or
>> ./convert-faq-to-pdf kinesis/data-streams
```


*For educational purposes only.*
