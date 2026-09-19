<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_2cp-b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="c_2cp-b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:skull-1-bold" {...props}></Icon>
