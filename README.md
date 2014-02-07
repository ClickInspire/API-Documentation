# Core APIs

## Scheduling

The purpose of this API is to create a BaaS for applications that rely on scheduling like abilities.

### Entities

- Availability
- AvailabilityException

- Company
- Professional
- Client
- Profile
- Resource

- Booking
- Reminder

- Industry
- Service

- ServiceConfiguration
- ResourceType
- ResourceOption

- GoogleCalendar
- GoogleBooking

- User

## Reclaim

The purpose of this API is to create a BaaS for applications to allow users to recover appointments.

## Entities

- RecoveryCampaign
- RecoveryTrigger

- RecoveryRule
- RecoveryRuleTimeSet
- RecoveryRuleService

- PromotionSettings

- Channel
- ChannelSettings

- SocialPost
- Share

- User

## Client Management

Communication and management of clients is quite different from scheduling. This API should host the chat functionality as well as any additional entities relating to a client that aren't mission critical for scheduling.

### Entities

*TBD*

# Supporting APIs

## Cron

The purpose of this API is to create a BaaS for triggering API request to other APIs at specific times.

### Entities

*TBD*

## Authentication

Provide a centralized place to authenticate socially and store related information.

- GoogleAuth
- FacebookAuth
- TwitterAuth

- User
