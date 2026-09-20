<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vukmy-a0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vukmy-a0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:volcano-11" {...props}></Icon>
