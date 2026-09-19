<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frffk_bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="frffk_bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:share-1" {...props}></Icon>
