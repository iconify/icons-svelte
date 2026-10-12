<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_g8s2ell.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r_g8s2ell"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:systemverilog" {...props}></Icon>
