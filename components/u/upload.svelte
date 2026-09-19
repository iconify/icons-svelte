<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp_816eks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lp_816eks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:upload" {...props}></Icon>
