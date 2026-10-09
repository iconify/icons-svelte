<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9rholkuw.css';
import '../../css/z/zr6v3gbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9rholkuw"/><path class="zr6v3gbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:share-20-bold" {...props}></Icon>
