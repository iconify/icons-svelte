<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spqow63td.css';
import '../../css/o/oodxeba0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spqow63td"/><path class="oodxeba0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-down-20-bold" {...props}></Icon>
