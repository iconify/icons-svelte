<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvy86qb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvy86qb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scoreboard-outline" {...props}></Icon>
