<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkyxxnwcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jkyxxnwcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:z-outline" {...props}></Icon>
