<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1p0lil_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1p0lil_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-low-01" {...props}></Icon>
