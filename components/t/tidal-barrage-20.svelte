<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2p_4xcpi.css';
import '../../css/g/gj10flppe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x2p_4xcpi"/><path class="gj10flppe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-barrage-20" {...props}></Icon>
