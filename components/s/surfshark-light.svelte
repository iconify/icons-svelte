<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwd2bzf6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rwd2bzf6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surfshark-light" {...props}></Icon>
