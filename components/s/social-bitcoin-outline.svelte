<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_isbccr.css';
import '../../css/g/gi_g19bwq.css';
import '../../css/h/hz35m3bwu.css';
import '../../css/y/yfygjjlft.css';
import '../../css/n/n9urvbcdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt_isbccr"/><path class="gi_g19bwq"/><path class="hz35m3bwu"/><path class="yfygjjlft"/><path class="n9urvbcdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-bitcoin-outline" {...props}></Icon>
