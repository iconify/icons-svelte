<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b462bm_4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b462bm_4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasmocompiler-light" {...props}></Icon>
