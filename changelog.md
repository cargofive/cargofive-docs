# Cargofive API
All notable changes to this project will be documented in this file.

## [2.0.0] - 2020-06-13
-----------------
### Added
- added new containers type: Reefer, Open Top and Flat Rack.
- added "type" parameter: DRY, REEFER, OPENTOP, FLATRACK (search rates).
- added "remarks" section (search rates).
- added endpoint with "nogroup" option to display ungrouped rates in the surcharges section (search rates).
### Changed
- "validity_start" replaced by "valid_from" in the quote information (Quotes).
- "validity_end" replaced by "valid_until" in the quote information (Quotes).
- "delivery_type" replaced by "delivery" in the quote information (Quotes).
- "validity_start" replaced by "valid_from" in "rates_v2" section (Quotes).
- "validity_end" replaced by "valid_until" in "rates_v2" section  (Quotes).
- "name_company" replaced by "company_name" in "user" section  (Quotes).
- "amount" replaced by "price" in "charge" section (Quotes).
- "markups" replaced by "markup" in "charge" section (Quotes).
- "total" replaced by "total_price" in the "charge" section (Quotes).
- "validity_start" replaced by "valid_from" in the "contract" section(Search rates).
- "validity_end" replaced by "valid_until" in the "contract" section (Search rates).
- "charge_freight" replaced by "freight_charges" in the resulting json when searching for rates.
- "charges_origin" replaced by "origin_charges" in the resulting json when searching for rates.
- "charges_destination" replaced by "destination_charges" in the resulting json when searching for rates.
- "amount" replaced by "price" in the resulting json when searching for rates.
- value for the "type" field in the resulting json when searching for rates (20DV,40DV,40HC,40NOR,45HC,20RF,40RF,20FR,40FR,20OT,40OT).
### Removed
- markup (+ container type) field was removed (Search rates).
- markupConvert (+ container type) field was removed (Search rates).
- typeMarkup (+ container type) field was removed (Search rates).
- monto (+ container type) field was removed (Search rates).
- montoMarkup (+ container type) field was removed (Search rates).
- The "position" field was removed from the "user" section (Quotes).
- The "access" field was removed from the "user" section (Quotes).
- The "verified" field was removed from the "user" section (Quotes).
- The "state" field was removed from the "user" section (Quotes).
- The "api_token" field was removed from the "user" section (Quotes).
- The "associated_quotes" field was removed from the "company" section (Quotes).
- The "company_user_id" field was removed from the "company" section (Quotes).
- The "api_id" field was removed from the "company" section (Quotes).
- The "api_status" field was removed from the "company" section (Quotes).
- The "pdf_language" field was removed from the "company" section (Quotes).
- The "payment_conditions" field was removed from the "company" section (Quotes).

## [1.7.0] - 2020-05-22
-----------------
### Added
- added carrier's details (search rates).
- added "paginate" parameter to paginate responses.
### Removed
- endpoint to get local charges list.
- endpoint to get rates list.

## [1.6.0] - 2020-05-08
-----------------
### Added
- added options field to surcharges.
- added endpoints to store, update and delete surcharges.

## [1.5.0] - 2020-04-23
-----------------
### Added
- added "options" field to contacts.
- added "options" field to companies.
### Changed
- "contact" section, added "options" field (Quotes).
- "company" section, added "options" field (Quotes).
- "contact" section, added "options" field (Quote by ID).
- "company" section, added "options" field (Quote by ID).

## [1.4.0] - 2020-03-27
-----------------
### Added
- added "integration" parameter in quotes.
- added endpoint to download PDF documents.
- added endpoint to get surcharges list.

## [1.3.0] - 2020-03-20
-----------------
### Added
- added carrier's details (Quotes).
- added carrier's details (Quote by ID).
- added endpoint to get carriers list.
- added endpoint to get airlines list.
### Fixed
- error catching process.

## [1.2.1] - 2020-02-21
-----------------
### Added
- added "size" parameter to limit the size of the response.

## [1.2.0] - 2020-02-21
-----------------
### Added
- added endpoint to get carriers list.
- added endpoint to get airlines list.
- added endpoints to store, update and delete companies.
- added endpoints to store, update and delete contacts.

## [1.1.0] - 2019-08-23
-----------------
### Added
- added endpoint to get companies list.
- added endpoint to get contacts list.

## [1.0.0] - 2019-08-09
-----------------
### Added
- added endpoint to get quotes list.
- added endpoint to search rates with parameters.
- added endpoint to get local charges list.
- added endpoint to get rates list.


