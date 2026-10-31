<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg0a43ifq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg0a43ifq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-scorpio-fill-round" {...props}></Icon>
