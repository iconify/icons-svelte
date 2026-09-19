<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk0f0oa3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qk0f0oa3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-4-bold" {...props}></Icon>
