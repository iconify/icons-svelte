<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n20eu0b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n20eu0b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shoe-print-outline" {...props}></Icon>
