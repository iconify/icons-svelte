<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmmz9qtup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jmmz9qtup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ticket-duo" {...props}></Icon>
