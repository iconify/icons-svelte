<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-9x3oqjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":496};
const content = `<path class="k-9x3oqjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sort-desc" {...props}></Icon>
