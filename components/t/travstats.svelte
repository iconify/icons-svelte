<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob9sxvbzl.css';
import '../../css/w/wnxfwsbhv.css';
import '../../css/y/y87stwskn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ob9sxvbzl"/><path class="wnxfwsbhv"/><path class="y87stwskn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:travstats" {...props}></Icon>
