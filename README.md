# OpenInsights Community Presets

Official community presets for [OpenInsights](https://github.com/ertad-family/openinsights) - research project templates with pre-configured tags, metadata fields, and AI prompts.

## Available Presets

| Preset | Category | Description |
|--------|----------|-------------|
| [Usability Test Analysis](presets/usability-testing.json) | USABILITY | Track task completion, friction points, and user emotions |
| [Jobs-to-be-Done Interview](presets/jtbd-interview.json) | DISCOVERY | Analyze customer switching decisions using the JTBD framework |
| [Customer Feedback Synthesis](presets/customer-feedback.json) | VOICE_OF_CUSTOMER | Classify sentiment, topics, and actionability from feedback |
| [Competitor Analysis](presets/competitor-analysis.json) | COMPETITIVE | Compare feature parity and user perceptions |

## Structure

```
├── presets/
│   ├── usability-testing.json
│   ├── jtbd-interview.json
│   ├── customer-feedback.json
│   └── competitor-analysis.json
└── index.json              # Combined index (auto-fetched by OpenInsights)
```

## Usage

These presets are automatically fetched by OpenInsights when creating a new project. Select a preset from the dropdown to apply pre-configured:

- **Tags** - Taxonomy for categorizing highlights
- **Metadata Fields** - Custom fields for sources (participant info, device, etc.)
- **AI Prompts** - Prompts for auto-tagging and project summaries
- **Project Settings** - Default project type and goals

## Contributing

To add a new preset:

1. Create a new JSON file in `presets/` following the existing format
2. Update `index.json` to include the new preset
3. Submit a pull request

## License

MIT License - See [OpenInsights](https://github.com/ertad-family/openinsights) for details.
