<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e54sm5b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e54sm5b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:speech-bubble-conversation-fill-16" {...props}></Icon>
