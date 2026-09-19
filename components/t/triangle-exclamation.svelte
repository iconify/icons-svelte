<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8zp1_bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8zp1_bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:triangle-exclamation" {...props}></Icon>
