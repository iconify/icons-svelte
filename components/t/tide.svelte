<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo4jxcygl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xo4jxcygl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:tide" {...props}></Icon>
