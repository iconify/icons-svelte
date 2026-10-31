<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rup412bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rup412bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-virgo-duotone-round" {...props}></Icon>
