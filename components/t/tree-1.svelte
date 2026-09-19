<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm0wchruk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wm0wchruk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-1" {...props}></Icon>
