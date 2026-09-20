<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj77yccnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dj77yccnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:secluso-light" {...props}></Icon>
