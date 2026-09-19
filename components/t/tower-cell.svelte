<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fut-rcs0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="fut-rcs0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tower-cell" {...props}></Icon>
