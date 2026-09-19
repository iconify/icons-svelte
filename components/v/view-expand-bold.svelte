<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkv818cfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tkv818cfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:view-expand-bold" {...props}></Icon>
