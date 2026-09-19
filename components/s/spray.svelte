<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_3fsb4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="h-_3fsb4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:spray" {...props}></Icon>
