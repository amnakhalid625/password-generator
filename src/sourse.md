usestate hook is responsible for the changing in the ui in the react 
when we change on the variable without the hook changing reflect on the
only console not on the ui so in the react useState hook is responsible 
to change the ui (means of the screen)

useCallback hook:

Call useCallback at the top level of your component to cache a function definition between re-renders:
( is ka matlab mery pass ik funtion ha usey jitna ho saky memory uni chache me rak lo.or phir jab me isy call karo to jitna part phly ka use ho wo karo baqi ka memory me hi rahny do)
(The useCallback hook is a performance optimization mechanism in React that helps prevent unnecessary re-renders of child components when their parent component re-renders.)

useCallback hook me ik function or ik dependency hoti
dependency means  k change hoty hi ik function run ho ga 

useEffect hook:useEffect is a React Hook that lets you synchronize a component with an external system.
Don’t rush to add Effects to your components. Keep in mind that Effects are typically used to “step out” of your React code and synchronize with some external system. This includes browser APIs, third-party widgets, network, and so on. If your Effect only adjusts some state based on other state, you might not need an Effect.


useRef hook:useref is a reference (jab mujy kisi b chiz ka reference lena hota ha to me useRef lny ha)


