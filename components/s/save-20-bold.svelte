<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnwkubctl.css';
import '../../css/z/znrt3ccop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wnwkubctl"/><path class="znrt3ccop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:save-20-bold" {...props}></Icon>
