<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8g5kacgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8g5kacgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unlocked-variant-outline" {...props}></Icon>
