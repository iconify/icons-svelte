<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xngcx7bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xngcx7bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:user-comment-outline" {...props}></Icon>
