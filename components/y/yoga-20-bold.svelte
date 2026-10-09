<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0h130b3n.css';
import '../../css/f/fml2kccmr.css';
import '../../css/s/se5adobpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b0h130b3n"/><path class="fml2kccmr"/><path class="se5adobpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yoga-20-bold" {...props}></Icon>
