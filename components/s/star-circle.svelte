<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxj0xs36a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="sxj0xs36a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:star-circle" {...props}></Icon>
