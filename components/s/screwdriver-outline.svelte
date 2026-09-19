<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l80po2zqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l80po2zqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:screwdriver-outline" {...props}></Icon>
