<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl_vlo1qn.css';
import '../../css/c/cmb2wab2t.css';
import '../../css/e/ez7qb80yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wl_vlo1qn"/><path class="cmb2wab2t"/><path clip-rule="evenodd" class="ez7qb80yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-query-ppl" {...props}></Icon>
