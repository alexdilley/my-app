<script>
  import { Component1 } from 'my-component-lib';

  let items = ['foo', 'bar', 'baz'];
</script>

<Component1 {items} let:item>
  <pre>{item}</pre>
</Component1>
