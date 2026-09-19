<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s093hob-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s093hob-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-06" {...props}></Icon>
