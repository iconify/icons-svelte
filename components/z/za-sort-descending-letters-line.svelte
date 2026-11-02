<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d11tu2hwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d11tu2hwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:za-sort-descending-letters-line" {...props}></Icon>
