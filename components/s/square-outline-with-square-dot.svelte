<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffogxa9fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ffogxa9fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:square-outline-with-square-dot" {...props}></Icon>
