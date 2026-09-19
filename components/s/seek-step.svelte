<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9krj_bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k9krj_bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-step" {...props}></Icon>
