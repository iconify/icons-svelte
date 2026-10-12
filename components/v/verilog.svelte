<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvpbptb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pvpbptb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:verilog" {...props}></Icon>
