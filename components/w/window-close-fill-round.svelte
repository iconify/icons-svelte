<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i91yb9t8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i91yb9t8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-close-fill-round" {...props}></Icon>
