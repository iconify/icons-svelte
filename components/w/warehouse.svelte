<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj53t6bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zj53t6bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:warehouse" {...props}></Icon>
