<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-1w2wbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="y-1w2wbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:share-from-square" {...props}></Icon>
