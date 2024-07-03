# ai-safe
**ai-safe** protecst your copyright from ai. It is a comprehensive solution for managing access to various types of digital resources (text, video, images, and audio) based on specific criteria such as license type, region, and country. It aims to protect and control the usage of content by AI crawlers, ensuring compliance with licensing terms and regional restrictions.

## Features

- **Resource Management**: Define allowed and disallowed resources with detailed metadata.
- **License Control**: Specify license types and restrictions for each resource.
- **Regional Restrictions**: Control access to resources based on geographic regions and specific countries.
- **Flexible JSON Schema**: Use a robust and extensible JSON schema for easy integration and management.

## Table of Contents

- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

## Usage

### Example Configuration

Below is an example of a configuration JSON file implementing restrictions to all content types, allowing access only for Europe.

```json
{
  "title": "ai-safe"
  "resources": {
    "allowed-resources": [
      {
        "url": "/",
        "type": "source-code",
        "license": {
          "type": "*"
        },
        "region": ["EU"],
        "countries": ["*"]
      }
    ]
  }
}


## Contributing

We welcome contributions to improve **ai-safe**. Please follow the standard GitHub workflow to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

## Contact

For any questions or feedback, please reach out to [andrea.zanda@rombo.ai].

---

Thank you for using **ai-safe**! We hope it helps you manage and protect your digital resources effectively.


