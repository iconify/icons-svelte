<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc5w5cbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wc5w5cbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sailboat" {...props}></Icon>
