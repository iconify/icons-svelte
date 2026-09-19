<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_wfxg79v.css';
import '../../css/s/sezprjuom.css';
import '../../css/g/gz7pb0bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_wfxg79v"/><path class="sezprjuom"/><path class="gz7pb0bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-asset-view" {...props}></Icon>
