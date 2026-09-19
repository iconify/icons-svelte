<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs84ht5uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hs84ht5uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:spinner-2" {...props}></Icon>
