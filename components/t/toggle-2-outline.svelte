<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r75m5p1ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r75m5p1ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:toggle-2-outline" {...props}></Icon>
