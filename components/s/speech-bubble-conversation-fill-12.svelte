<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5gk22b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d5gk22b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-conversation-fill-12" {...props}></Icon>
