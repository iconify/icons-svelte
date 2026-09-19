<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1r8mg_ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="k1r8mg_ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:zotero" {...props}></Icon>
