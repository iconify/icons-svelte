<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzpx7fb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzpx7fb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:television-play" {...props}></Icon>
