<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij6dd8bdq.css';
import '../../css/p/psiwifbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ij6dd8bdq"/><path class="psiwifbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terraced-house-20" {...props}></Icon>
