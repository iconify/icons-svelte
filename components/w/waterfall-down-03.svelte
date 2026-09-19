<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd0v0ry5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd0v0ry5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:waterfall-down-03" {...props}></Icon>
