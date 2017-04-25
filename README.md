# React
React Homework Option 1


- Props
  - Props is short for properties.
  - They are part of a components configuration.
  - They are immutable (cannot be changed) within the component.
  - Props can change state, but should not be changed by state.
  - Props can change the way the state is rendered.

- State
  - Can be changed (mutable)
  - Can be passed to a child component as a prop
  - The state of an item is how it exists at any point in time/process.
  - The state of an item can be altered by a component.


- Props & State examples:

  - For a props/state example.  Let's consider my eyes.  They are hazel and my vision is not very good.

  - I cannot change the color of my eyes (prop).  I can add colored contact lens (state).  This will make my eyes appear to be a different color (render) but have not changed the prop.

  - Or, I can also added glasses (change the state) this will render better vision - but will not change the prop of my vision.
  


- Component Life Cycle

  - To understand Component Life Cycle.  It helps to understand components.  A component is a chunk of code that works like a function.  It can be called with prop and render the results to the screen (that is the most common, but not the only thing a component can do).  When a component renders something to the (Document Object Model) DOM it is "mounted".  When it is removed from the DOM it is "unmounted".  Many component life cycles contain the words "did" or "will", such as componentWillMount.  Life cycle methods that contain the work "will" happen just before a something happens.  Methods that contain the word "did" happen just after something happens.
  
  





