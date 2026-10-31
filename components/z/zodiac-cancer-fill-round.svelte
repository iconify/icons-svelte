<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss2l69fuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss2l69fuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-cancer-fill-round" {...props}></Icon>
