<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtdpo8psi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vtdpo8psi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ticket" {...props}></Icon>
