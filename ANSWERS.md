1. What are PropTypes used for?

PropTypes are a way for developers to catch bugs before they happen. We can define what kind of data we want going where, this way we ensure that our components are getting exactly what they need and won't throw unnecessary errors.


2. Describe a life-cycle event in React.

One life-cycle event is the Mounting phase, also known as the birth phase. This is the phase when the component is originally being built. The constructor will take the intitial data you have, and the rendor method is called to render anything you've built. The componentDidMount method is also called here.


3. Explain the details of a Higher Order Component.

A higher order component is a component that receives components as arguments, and returns a new component. Higher order components can be used to take advantage of some shared functionality between componenets so we're not repeating ourselves, and they can also be used to perform logic, like a Login page on a website.


4. What are three different ways to style components in React? Explain some of the benefits of each.

One way is just plain old vanilla CSS. A benefit of this is that it's simple, and you don't need to install or know how to use any other possible dependencies beyond vanilla CSS. You could also use a preprocessor, such as Less or SASS. These of course come with the goodies of preprocessing, like nesting, mixins, variables, compartmentalized style sheets, etc. Lastly are Styled Components. Styled Components are great because they give us the ability to write CSS right in our javascript. This gives us options like conditional rendoring, or using logic with our CSS, which can be very powerful. Styled Components can also be written right in our javascript files, which can help keep files clutter to a minimum.