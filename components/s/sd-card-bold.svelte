<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecmp83b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ecmp83b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sd-card-bold" {...props}></Icon>
