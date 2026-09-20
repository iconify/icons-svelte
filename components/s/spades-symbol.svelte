<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-c0ls6qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w-c0ls6qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spades-symbol" {...props}></Icon>
