<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upi0unbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="upi0unbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:users-bold" {...props}></Icon>
