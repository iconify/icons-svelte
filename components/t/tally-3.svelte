<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igi1yv4ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igi1yv4ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tally-3" {...props}></Icon>
