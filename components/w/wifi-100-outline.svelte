<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba_ehlbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ba_ehlbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-100-outline" {...props}></Icon>
