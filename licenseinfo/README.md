# Readme on licenseinfo

- The config.json file is loaded by MMF3 to determine the price etc to display in-app. See `LicenseConfig.swift` for the interface code.
- Make sure you're not mispelling anything or forgetting any commas, otherwise MMF will fall back to hardcoded values.
  - Countries are specified by BCP 47 Region Identifiers. For example "IN" for India. Also see ([BCP 47 Search](https://www.techonthenet.com/js/language_tags.php))
