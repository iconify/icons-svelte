<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1c7fbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="da1c7fbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:truck-filled" {...props}></Icon>
