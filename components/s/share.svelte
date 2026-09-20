<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn2ue_csy.css';
import '../../css/p/p6thd6bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zn2ue_csy"/><path class="p6thd6bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:share" {...props}></Icon>
