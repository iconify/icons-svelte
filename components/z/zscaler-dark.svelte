<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn2b2unhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yn2b2unhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zscaler-dark" {...props}></Icon>
