<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw04xcb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":778,"height":222};
const content = `<path class="dw04xcb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:volta-light" {...props}></Icon>
