<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6s0uv0ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w6s0uv0ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spack" {...props}></Icon>
