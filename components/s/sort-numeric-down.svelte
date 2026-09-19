<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr2383hrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vr2383hrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-numeric-down" {...props}></Icon>
