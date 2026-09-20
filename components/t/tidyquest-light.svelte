<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkcbdbnge.css';
import '../../css/r/rdd8ibbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fkcbdbnge"/><path class="rdd8ibbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidyquest-light" {...props}></Icon>
