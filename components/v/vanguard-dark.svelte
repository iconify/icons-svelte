<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt-qc4b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt-qc4b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vanguard-dark" {...props}></Icon>
