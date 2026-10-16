<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gza0lnxru.css';
import '../../css/e/e6mnr5buq.css';
import '../../css/j/jcyd-oqqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gza0lnxru"/><path class="e6mnr5buq"/><path class="jcyd-oqqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:xor-gate-20" {...props}></Icon>
