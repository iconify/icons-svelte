<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_o20eohb.css';
import '../../css/f/f23s2bc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="p_o20eohb"/><path class="f23s2bc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-filled" {...props}></Icon>
