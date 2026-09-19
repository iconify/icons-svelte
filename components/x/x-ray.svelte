<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuvh9jb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zuvh9jb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:x-ray" {...props}></Icon>
