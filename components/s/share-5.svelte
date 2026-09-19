<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kktn4_nwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="kktn4_nwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:share-5" {...props}></Icon>
