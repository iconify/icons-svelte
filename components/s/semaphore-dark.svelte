<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh4x1nwdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wh4x1nwdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:semaphore-dark" {...props}></Icon>
