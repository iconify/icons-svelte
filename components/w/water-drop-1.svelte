<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmynu6bpt.css';
import '../../css/c/c8_g7taxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="lmynu6bpt"/><path clip-rule="evenodd" class="c8_g7taxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:water-drop-1" {...props}></Icon>
