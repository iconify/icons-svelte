<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0vonts3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="i0vonts3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:volume-none" {...props}></Icon>
