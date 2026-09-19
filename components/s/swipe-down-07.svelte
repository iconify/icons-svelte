<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1e3d9t9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1e3d9t9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:swipe-down-07" {...props}></Icon>
