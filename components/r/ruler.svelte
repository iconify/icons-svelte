<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx0z7v04o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xx0z7v04o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ruler" {...props}></Icon>
