<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7lu8lw2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":83.196};
const content = `<path class="r7lu8lw2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vudu" {...props}></Icon>
