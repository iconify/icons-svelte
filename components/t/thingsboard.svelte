<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfan_xeus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xfan_xeus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:thingsboard" {...props}></Icon>
