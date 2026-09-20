<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv0qo_yvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv0qo_yvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-check" {...props}></Icon>
