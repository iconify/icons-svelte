<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj1u2fbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":496};
const content = `<path class="hj1u2fbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sort-asc" {...props}></Icon>
