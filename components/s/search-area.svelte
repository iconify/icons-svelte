<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm2yxmd5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm2yxmd5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-area" {...props}></Icon>
