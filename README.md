# py-spark-demo

# Faker Library Overview

The `Faker` library can generate a wide variety of random data types, making it useful for creating sample data for testing and development. Here are some of the most important data types and functionalities `Faker` provides:

## 1. Personal Information
- **Name**: `fake.name()`, `fake.first_name()`, `fake.last_name()`, `fake.prefix()` (e.g., Mr., Ms., Dr.), `fake.suffix()`
- **Address**: `fake.address()`, `fake.street_address()`, `fake.city()`, `fake.state()`, `fake.zipcode()`, `fake.country()`
- **Phone Number**: `fake.phone_number()`
- **Email**: `fake.email()`, `fake.free_email()`, `fake.company_email()`

## 2. Internet and Technology
- **Username**: `fake.user_name()`
- **Password**: `fake.password()`
- **IP Address**: `fake.ipv4()`, `fake.ipv6()`
- **MAC Address**: `fake.mac_address()`
- **URL**: `fake.url()`, `fake.image_url()`
- **Domain**: `fake.domain_name()`, `fake.domain_word()`, `fake.tld()` (top-level domain, e.g., .com, .org)

## 3. Financial
- **Credit Card**: `fake.credit_card_number()`, `fake.credit_card_provider()`, `fake.credit_card_security_code()`
- **Currency**: `fake.currency()`, `fake.currency_code()`
- **SSN/Insurance Numbers**: `fake.ssn()` (US social security number), `fake.ein()` (employer identification number)

## 4. Dates and Times
- **Date/Time**: `fake.date()`, `fake.time()`, `fake.date_time()`, `fake.iso8601()`
- **Future/Past Dates**: `fake.date_time_this_century()`, `fake.date_this_year()`, `fake.date_time_between()`
- **Date Ranges**: `fake.date_time_between_dates(start_date, end_date)`

## 5. Text and Writing
- **Paragraphs and Sentences**: `fake.paragraph()`, `fake.sentence()`, `fake.text()`
- **Words**: `fake.word()`, `fake.words()`
- **Lorem Ipsum Text**: `fake.lorem_text()`, `fake.lorem_words()`, `fake.lorem_paragraph()`

## 6. Commerce and Business
- **Company**: `fake.company()`, `fake.company_suffix()`
- **Job/Position**: `fake.job()`, `fake.bs()` (business jargon)
- **Currency**: `fake.currency_name()`, `fake.currency_code()`

## 7. Geographical and Location Data
- **Country and Locale**: `fake.country()`, `fake.country_code()`
- **City**: `fake.city()`, `fake.city_suffix()`
- **Latitude and Longitude**: `fake.latitude()`, `fake.longitude()`, `fake.coordinate()`

## 8. Identifiers and Unique Keys
- **UUID**: `fake.uuid4()` (unique identifier)
- **Random Integers**: `fake.random_int()`, `fake.random_number()`
- **EAN/UPC** (for products): `fake.ean()`, `fake.ean13()`

## 9. Customized Data and Miscellaneous
- **Boolean**: `fake.boolean()`
- **Binary Data**: `fake.binary()`
- **Color**: `fake.color_name()`, `fake.hex_color()`
- **File Names**: `fake.file_name()`, `fake.file_extension()`
- **Gender**: `fake.prefix()` (gender-neutral prefixes like Dr.), `fake.suffix()`
- **License Plates**: `fake.license_plate()`

## 10. Localized Data,
- **Localized Faker Providers**: Faker can generate data specific to different countries/locales (e.g., en_US, fr_FR, ja_JP), which changes formats for addresses, phone numbers, names, etc.
