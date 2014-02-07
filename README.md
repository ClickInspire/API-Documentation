# Separation of responsibility

### Scheduling

The purpose of this API is to create a BaaS for applications that rely on scheduling like abilities.

#### Entities

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

### Reclaim

The purpose of this API is to create a BaaS for applications to allow users to recover appointments.

### Entities

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

### Client Management

Management of client information and ratings is quite different from scheduling. This API should host as any additional entities relating to a client that aren't mission critical for scheduling. Almost like a CRM...

#### Entities

*TBD*

### Communication

Communication such as automatic sms vs app messaging toggle, monitoring of chat rooms for notifications to send push notifications, and email templates can be hosted here.

#### Entities

*TBD*

### Cron

The purpose of this API is to create a BaaS for triggering API request to other APIs at specific times.

#### Entities

*TBD*

### Authentication

Provide a centralized place to authenticate socially and store related information.

- GoogleAuth
- FacebookAuth
- TwitterAuth

- User
