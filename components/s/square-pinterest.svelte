<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smbwhr9xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="smbwhr9xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-pinterest" {...props}></Icon>
