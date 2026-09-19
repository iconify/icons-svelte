<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe4d_o0pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xe4d_o0pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:wasp" {...props}></Icon>
