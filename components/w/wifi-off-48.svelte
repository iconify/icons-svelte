<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzac5pbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rzac5pbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-off-48" {...props}></Icon>
