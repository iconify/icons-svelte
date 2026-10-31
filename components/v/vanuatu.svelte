<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmdi9b5k.css';
import '../../css/s/s50x3_b2i.css';
import '../../css/o/o2tb1bdsp.css';
import '../../css/c/cetjp6fgq.css';
import '../../css/d/dhc9u21yx.css';
import '../../css/p/pyji0cf5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="gmmdi9b5k"/><path class="s50x3_b2i"/><path class="o2tb1bdsp"/><path class="cetjp6fgq"/><path class="dhc9u21yx"/><path class="pyji0cf5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:vanuatu" {...props}></Icon>
