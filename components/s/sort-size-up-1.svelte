<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg86byjmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tg86byjmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-size-up-1" {...props}></Icon>
