<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4m2zw2yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z4m2zw2yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stop-circle-bold" {...props}></Icon>
