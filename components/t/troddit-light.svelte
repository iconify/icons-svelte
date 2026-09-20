<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsjgm3bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsjgm3bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:troddit-light" {...props}></Icon>
