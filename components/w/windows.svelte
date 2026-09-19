<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inzkwub1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="inzkwub1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:windows" {...props}></Icon>
