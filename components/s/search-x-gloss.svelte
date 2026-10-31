<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc34w8bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc34w8bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:search-x-gloss" {...props}></Icon>
