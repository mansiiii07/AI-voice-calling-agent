# AI-voice-calling-agent
Autonomous AI call agent that calls leads, qualifies them, books appointments and updates CRM on autopilot. Built with n8n, Vapi, Twilio, OpenAI and GoHighLevel.

## Tech Stack
- **n8n** — Workflow orchestration
- **Vapi** — Voice AI platform
- **Twilio** — Phone number and call routing
- **OpenAI** — Lead qualification and conversation intelligence
- **GoHighLevel** — CRM and appointment booking

## How It Works
1. New lead enters GoHighLevel CRM
2. n8n workflow triggers outbound call via Vapi
3. AI agent calls the lead and qualifies them
4. Appointment booked directly into GHL calendar
5. CRM updated automatically with call summary and outcome

## Features
- 24/7 autonomous outbound calling
- Real-time lead qualification
- Automatic appointment booking
- CRM auto-update after every call
- Handles up to 300 calls per day

## Setup
1. Clone this repo
2. Import workflow JSON into n8n
3. Add API keys for Vapi, OpenAI, Twilio, GoHighLevel
4. Configure GHL webhook
5. Test with your own phone number

## Author
Mansi Rathi — [github.com/mansiiii07](https://github.com/mansiiii07)
