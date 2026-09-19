<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2qc79brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2qc79brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:stumbleupon" {...props}></Icon>
