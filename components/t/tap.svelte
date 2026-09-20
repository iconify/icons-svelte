<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/movx4_hai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="movx4_hai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tap" {...props}></Icon>
