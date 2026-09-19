<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrt-k2bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zrt-k2bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbs-up-double" {...props}></Icon>
