<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6r-gxbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="y6r-gxbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:th" {...props}></Icon>
