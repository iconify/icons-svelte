<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv62zlbwh.css';
import '../../css/r/rpzzz8b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv62zlbwh"/><path class="rpzzz8b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:satellite-dish-filled" {...props}></Icon>
