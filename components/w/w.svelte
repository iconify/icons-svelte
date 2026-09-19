<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5v7lfww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ap5v7lfww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:w" {...props}></Icon>
