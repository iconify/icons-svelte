<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq_t2cbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq_t2cbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-bolt" {...props}></Icon>
