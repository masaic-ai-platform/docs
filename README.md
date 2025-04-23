# OpenResponses Documentation

This repository contains the documentation for OpenResponses, built with [Mintlify](https://mintlify.com/).


## Getting Started

### Prerequisites

- Node.js (14 or higher)
- npm or yarn

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/masaic-ai-platform/open-responses-docs.git
   cd open-responses-docs
   ```

2. Install the Mintlify CLI to preview the documentation changes locally:
   ```bash
   npm i -g mintlify
   ```

3. Start the development server:
   ```bash
   mintlify dev
   ```

   The documentation will be available at [http://localhost:3000](http://localhost:3000).

## Documentation Structure

- `docs.json` - Configuration file for the documentation structure
- `introduction.mdx` - Main landing page
- Other directories contain specific sections of the documentation

## Adding New Content

### Adding a New Page

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter at the top:
   ```mdx
   ---
   title: 'Page Title'
   description: 'Brief description of the page content'
   ---
   ```
3. Add the page to the navigation structure in `docs.json`

### Adding Use Cases & Demos

New use cases and demos should be added to the `use-cases/` directory:

1. Create a new `.mdx` file in the `use-cases/` directory
2. Add the file path to the "Use Cases & Demos" section in `docs.json`

## Configuration

The main configuration file is `docs.json`, which controls:

- Navigation structure
- Theme settings
- Global anchors and links
- SEO settings

## Deployment

The documentation is automatically deployed when changes are pushed to the main branch.

## Best Practices

- Use consistent formatting across all documentation files
- Include code examples where appropriate
- Use H2 (`##`) and H3 (`###`) headings for proper section organization
- Add descriptive alt text for any images

## Help and Support

If you have any questions or issues with the documentation, please reach out to the team on [Discord](https://discord.com/channels/1335132819260702723/1354795442004820068). 
