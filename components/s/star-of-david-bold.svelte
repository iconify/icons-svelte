<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ku_nt-d.css';
import '../../css/q/q4k0wbbrb.css';
import '../../css/y/yi5t2jbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="j5ku_nt-d"><path class="q4k0wbbrb"/><path class="yi5t2jbyt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:star-of-david-bold" {...props}></Icon>
