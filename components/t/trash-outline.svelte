<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx8dsuc6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bx8dsuc6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trash-outline" {...props}></Icon>
