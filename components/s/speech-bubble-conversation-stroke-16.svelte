<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsiypbdek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wsiypbdek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-conversation-stroke-16" {...props}></Icon>
