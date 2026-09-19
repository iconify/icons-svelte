<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p160bbc6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p160bbc6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:share-alt-square" {...props}></Icon>
