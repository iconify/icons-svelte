<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5b1z1hca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5b1z1hca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scoreboard" {...props}></Icon>
