<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lga8dlbkm.css';
import '../../css/x/x9stnobdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lga8dlbkm"/><path class="x9stnobdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wintry-mix" {...props}></Icon>
