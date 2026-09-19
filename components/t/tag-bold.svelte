<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a71-6xbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="a71-6xbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tag-bold" {...props}></Icon>
