# vue-infinite-loop-bug

 * Create an empty vue project
 * From your App component include a custom component from `./outer/Foo.vue`
 * From your outer component include an inner component from `./inner/Foo.vue`
 * Expected: The App is rendered with the outer component containing the inner component
 * Actual: The outer component is rendered in an infinite loop and a "Maximum call stack size exceeded" error occurs.
