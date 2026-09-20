<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojt__3bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ojt__3bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:turntable" {...props}></Icon>
