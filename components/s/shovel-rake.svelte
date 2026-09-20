<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fleuerbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fleuerbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shovel-rake" {...props}></Icon>
