<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z22p2s54p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z22p2s54p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aquarius-duotone-round" {...props}></Icon>
