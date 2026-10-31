<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri96t0v6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri96t0v6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tally-2-fill-round" {...props}></Icon>
