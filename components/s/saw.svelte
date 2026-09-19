<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxyxo_byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="jxyxo_byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:saw" {...props}></Icon>
