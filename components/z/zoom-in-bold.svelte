<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kszna-b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="kszna-b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zoom-in-bold" {...props}></Icon>
