<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs6sa0e_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gs6sa0e_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:uv" {...props}></Icon>
