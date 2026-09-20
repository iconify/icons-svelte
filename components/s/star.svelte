<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bslyux_4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bslyux_4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:star" {...props}></Icon>
