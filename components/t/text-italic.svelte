<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwec1599h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwec1599h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-italic" {...props}></Icon>
