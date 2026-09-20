<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kln7xeb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kln7xeb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-42" {...props}></Icon>
