<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxbxlac5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxbxlac5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-2-fill" {...props}></Icon>
