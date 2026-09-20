<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjeu243wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zjeu243wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:underline-u" {...props}></Icon>
