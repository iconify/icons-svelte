<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmhpr2b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vmhpr2b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ruler-combined-solid" {...props}></Icon>
