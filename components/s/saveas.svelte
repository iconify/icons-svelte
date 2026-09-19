<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jjbkisfvx.css';
import '../../css/c/cvjo67o6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="jjbkisfvx"/><path class="cvjo67o6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:saveas" {...props}></Icon>
