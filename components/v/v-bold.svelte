<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndygms9ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ndygms9ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:v-bold" {...props}></Icon>
