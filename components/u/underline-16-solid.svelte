<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydcngk_0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ydcngk_0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:underline-16-solid" {...props}></Icon>
