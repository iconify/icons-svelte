<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8_bm6x1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8_bm6x1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:turn-left-bold" {...props}></Icon>
