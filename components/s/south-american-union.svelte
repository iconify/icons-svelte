<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jztn7z8ge.css';
import '../../css/x/x47r2-ccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jztn7z8ge"/><path class="x47r2-ccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:south-american-union" {...props}></Icon>
