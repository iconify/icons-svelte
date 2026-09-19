<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks26x0d-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="ks26x0d-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shield-check" {...props}></Icon>
