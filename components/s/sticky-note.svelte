<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq-c0rbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1600};
const content = `<path class="aq-c0rbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:sticky-note" {...props}></Icon>
