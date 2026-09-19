<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thgsep5_e.css';
import '../../css/i/ift-4msrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="thgsep5_e"/><path class="ift-4msrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-creation" {...props}></Icon>
