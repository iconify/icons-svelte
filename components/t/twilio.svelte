<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5-mcp-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ch5-mcp-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:twilio" {...props}></Icon>
