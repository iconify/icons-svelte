<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8cnf1h0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h8cnf1h0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trash-1-bold" {...props}></Icon>
