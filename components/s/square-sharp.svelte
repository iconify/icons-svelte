<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3-85c9ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3-85c9ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:square-sharp" {...props}></Icon>
