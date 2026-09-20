<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uthf9xbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="uthf9xbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:town-11" {...props}></Icon>
