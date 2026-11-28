<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx-8u-k7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx-8u-k7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-refresh" {...props}></Icon>
