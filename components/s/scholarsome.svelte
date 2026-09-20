<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mttdjus_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mttdjus_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scholarsome" {...props}></Icon>
