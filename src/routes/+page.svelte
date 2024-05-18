<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
<input/>
<select>
    <option>Option</option>
    <option>Option 1</option>
    <option>Option 2</option>
</select>
<button>button</button>

<style lang="scss">
    //@use "../styles/functions";
    // @use "@unsass/breakpoint";
  h1 {
    color: red;
    font-size: functions.toRem(36);
    // u can use only down, on place of up
    @include breakpoint.up('md'){
        color: green;
    }
    @include breakpoint.up('lg'){
        color: blue
    }
  }
</style>
