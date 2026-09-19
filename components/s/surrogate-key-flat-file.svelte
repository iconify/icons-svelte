<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps-inobsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ps-inobsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:surrogate-key-flat-file" {...props}></Icon>
