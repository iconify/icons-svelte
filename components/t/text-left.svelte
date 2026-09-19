<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdjmcvblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zdjmcvblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-left" {...props}></Icon>
