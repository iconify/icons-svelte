<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaszo0-_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yaszo0-_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:stile-squeezer" {...props}></Icon>
