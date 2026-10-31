<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl2ya4fxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2ya4fxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:soup-round" {...props}></Icon>
