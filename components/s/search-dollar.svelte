<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksl-n8z_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksl-n8z_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:search-dollar" {...props}></Icon>
