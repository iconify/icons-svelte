<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_gi64bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_gi64bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sponsorblock-dark" {...props}></Icon>
