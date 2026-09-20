<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ear-7c2pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ear-7c2pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-8" {...props}></Icon>
