<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y92m0cfbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":384};
const content = `<path class="y92m0cfbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-array" {...props}></Icon>
