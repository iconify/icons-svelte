<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t519h8eza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t519h8eza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sparkle" {...props}></Icon>
