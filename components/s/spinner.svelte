<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq88fx61h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sq88fx61h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:spinner" {...props}></Icon>
