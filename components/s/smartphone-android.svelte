<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxu4w7lou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":480};
const content = `<path class="nxu4w7lou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-android" {...props}></Icon>
