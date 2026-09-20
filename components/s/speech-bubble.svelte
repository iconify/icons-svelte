<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1uxf8r0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n1uxf8r0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:speech-bubble" {...props}></Icon>
