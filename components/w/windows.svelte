<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4nnf_b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r4nnf_b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:windows" {...props}></Icon>
