# Bot for Asi - Real Estate Lead Generation WhatsApp Bot

## Overview
A WhatsApp-based conversational UI that replaces static lead forms for real estate listings. The bot engages potential buyers of new construction properties in natural dialogue to capture leads.

## Features
- Natural Hebrew language conversation
- Project matching based on user preferences
- Lead data capture and qualification
- Feedback collection and analytics
- Daily performance summaries

## Project Structure
```
.
├── .github/
│   └── workflows/       # CI/CD pipeline configurations
├── docs/
│   ├── flows/          # Conversation flow documentation
│   ├── schemas/        # Database and YAML schemas
│   └── stories/        # User stories and requirements
├── src/
│   ├── database/       # Database integration
│   └── make-scenarios/ # MAKE.com automation scenarios
└── README.md
```

## Technical Stack
- Platform: WhatsApp Business API (via Twilio/Gupshup)
- Automation: MAKE.com
- Database: Supabase
- Flow Definition: YAML-based
- Language: Hebrew (עברית)

## Key Components
1. **Conversation Flow**
   - Welcome and purpose explanation
   - User intent collection
   - Project recommendations
   - Lead capture
   - Feedback collection

2. **Data Collection**
   - User preferences (location, budget, rooms)
   - Contact information
   - Session metrics
   - User feedback

3. **Analytics**
   - Daily performance summaries
   - Feedback analysis
   - Conversion tracking

## Getting Started
1. Clone the repository
2. Set up MAKE.com workspace
3. Configure Supabase connection
4. Set up WhatsApp Business API
5. Deploy YAML flows

## Configuration
Required environment variables:
- `OPERATIONS_EMAIL`: Email for operations team
- `PRODUCT_EMAIL`: Email for product team
- `WHATSAPP_API_KEY`: WhatsApp Business API key
- `SUPABASE_URL`: Supabase project URL
- `SUPABASE_KEY`: Supabase API key

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is proprietary and confidential.

## Contact
For any questions or support, please contact the development team.