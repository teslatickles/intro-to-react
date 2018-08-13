1. The essential differences between `props` and `states` are that `props` are __immutable__, meaning they can not be changed once created. You, the user, pass properties to your componentvia `props`, and at this point that info passed is not able to be changed. `Props` are considered "external", being controlled by the thing that renders the component. `State` is considered "internal" and controlled by the component itself. `States` are not __immutable__, meaning they can change. This makes `states` quite useful when considering data that needs to be updated in real-time or dynamically as being displayed. A component without `state`, if possible, is preferable as it's more predictable and increases complexity. 

1. Read the documentation. 

1. See file: [https://github.com/teslatickles/intro-to-react/blob/master/greeting.html](`greeting.html`)


