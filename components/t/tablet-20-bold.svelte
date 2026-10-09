<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byse_4bgl.css';
import '../../css/j/j17_kebzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="byse_4bgl"/><path class="j17_kebzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tablet-20-bold" {...props}></Icon>
