<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vupwwln_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vupwwln_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-low-20" {...props}></Icon>
