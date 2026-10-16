<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6hkjmaim.css';
import '../../css/j/j9quaibxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x6hkjmaim"/><path class="j9quaibxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spillway-20-bold" {...props}></Icon>
