# Magazine Subscription Service
### Completed coursework · ICT373 Software Architecture and Design

A Java subscription-management application, developed first as a console program and then as a JavaFX desktop interface.

## What I built
- Paying, self-paying and associate customer models in the console version.
- Magazine and supplement selection.
- Printed weekly subscription messages and invoice calculations.
- JavaFX Create, Edit and View screens.
- Address/payment abstractions and local file persistence in the desktop version.

## Design focus
The project uses inheritance for customer types, a payment-method interface, and composition for customer relationships and subscriptions. The desktop version separates FXML layouts, controllers and domain models, while retaining some business logic in its controllers.

## Verification
Both application versions compile. The console sample workflow and billing totals were checked. An integration check verifies duplicate-subscription handling, billing and a save/load round trip that preserves sponsor and shared-supplement relationships. All three FXML layouts parse; interactive GUI behaviour has not been tested.

Completed coursework does not mean a production billing platform. Messages are printed locally, and payment methods are demonstration models. No emails are sent and no payments are processed.

[← Back to my profile](https://github.com/Ginnnyyyy#completed-projects)
