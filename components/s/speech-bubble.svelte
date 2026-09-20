<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a63_o0bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="a63_o0bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:speech-bubble" {...props}></Icon>
