<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi7c8xbbv.css';
import '../../css/j/j04y387jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oi7c8xbbv"/><path class="j04y387jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xbox-game-pass" {...props}></Icon>
