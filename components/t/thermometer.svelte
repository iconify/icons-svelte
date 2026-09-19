<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shyve_bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shyve_bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thermometer" {...props}></Icon>
