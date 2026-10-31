<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1pt29g_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pt29g_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-scorpio-duotone-round" {...props}></Icon>
