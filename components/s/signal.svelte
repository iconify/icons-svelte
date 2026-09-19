<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncqz1lymk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ncqz1lymk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal" {...props}></Icon>
