<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rco92cb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="rco92cb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:telephone-11" {...props}></Icon>
