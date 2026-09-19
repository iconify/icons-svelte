<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx_5pr5ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tx_5pr5ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-75" {...props}></Icon>
