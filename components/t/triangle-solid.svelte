<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ips20vbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ips20vbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-solid" {...props}></Icon>
