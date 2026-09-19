<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e50ycdctt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="e50ycdctt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:virus-bold" {...props}></Icon>
