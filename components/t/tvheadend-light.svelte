<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfow1tlzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dfow1tlzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tvheadend-light" {...props}></Icon>
