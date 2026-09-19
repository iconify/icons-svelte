<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/das0gdcyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="das0gdcyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:stumbleupon" {...props}></Icon>
