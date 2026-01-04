# Chickenfarm

A test repository for Rocketship test suites.

## Structure

```
.
├── .rocketship/           # Root-level test suites
├── api/.rocketship/       # API test suites
└── react/.rocketship/     # React frontend test suites
```

## Running Tests

```bash
# Run all tests in a directory
rocketship run -d api/.rocketship

# Run a specific test suite
rocketship run -f .rocketship/user-onboarding-journey.yaml
```

## Test Suites

### Root (.rocketship/)
- `user-onboarding-journey.yaml` - User onboarding flow

### API (api/.rocketship/)
- `user-content-management-journey.yaml` - Content CRUD operations
- `user-preferences-journey.yaml` - User preferences and localization
- `user-payment-journey.yaml` - Payment flow

### React (react/.rocketship/)
- `user-browsing-journey.yaml` - Product browsing
- `user-feedback-journey.yaml` - User feedback flow
- `user-submission-journey.yaml` - Form submissions
