<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzip_vo3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zzip_vo3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:windsurf-dark" {...props}></Icon>
