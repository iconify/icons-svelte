<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5jgqf6cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1536};
const content = `<path class="p5jgqf6cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:trophy" {...props}></Icon>
