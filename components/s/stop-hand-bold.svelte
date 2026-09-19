<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx7u_3bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xx7u_3bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stop-hand-bold" {...props}></Icon>
