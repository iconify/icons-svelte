<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui32i6m3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ui32i6m3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:waves-bold" {...props}></Icon>
