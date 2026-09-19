<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi2813bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mi2813bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:thumb-up-down" {...props}></Icon>
