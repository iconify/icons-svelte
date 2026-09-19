<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7_8i1o_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="l7_8i1o_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:star-outline" {...props}></Icon>
