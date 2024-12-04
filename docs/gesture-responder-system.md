

The gesture responder system manages the lifecycle of gestures in your app. A touch can go through several phases as the app determines what the user's intention is. For example, the app needs to determine if the touch is scrolling, sliding on a widget, or tapping. This can even change during the duration of a touch. There can also be multiple simultaneous touches.

The touch responder system is needed to allow components to negotiate these touch interactions without any additional knowledge about their parent or child components.

### Best Practices

To make your app feel great, every action should have the following attributes:

- Feedback/highlighting- show the user what is handling their touch, and what will happen when they release the gesture
- Cancel-ability- when making an action, the user should be able to abort it mid-touch by dragging their finger away

These features make users more comfortable while using an app, because it allows people to experiment and interact without fear of making # TouchableHighlight and 

The responde

A view can become the touch responder by implementing the correct negotiation methods. There are two methods to ask the view if it wants to become responder:

- interpretation, check out [PanResponder](panresponder.md).
