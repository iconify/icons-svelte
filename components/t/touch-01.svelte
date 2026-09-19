<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du0_gub6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du0_gub6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-01" {...props}></Icon>
