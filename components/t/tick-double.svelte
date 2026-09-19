<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq3_sibjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lq3_sibjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:tick-double" {...props}></Icon>
