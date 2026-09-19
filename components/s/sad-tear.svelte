<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty2bzmojf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ty2bzmojf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sad-tear" {...props}></Icon>
