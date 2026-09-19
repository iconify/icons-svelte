<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd4gsf7oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zd4gsf7oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-1-outline" {...props}></Icon>
