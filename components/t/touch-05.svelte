<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0-d_4-vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0-d_4-vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-05" {...props}></Icon>
