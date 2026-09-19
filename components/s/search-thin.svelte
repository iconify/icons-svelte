<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zug9xsbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zug9xsbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:search-thin" {...props}></Icon>
