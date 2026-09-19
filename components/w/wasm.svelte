<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihlz0wbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ihlz0wbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wasm" {...props}></Icon>
