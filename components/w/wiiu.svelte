<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3r3u6_tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3r3u6_tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wiiu" {...props}></Icon>
