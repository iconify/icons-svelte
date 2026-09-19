<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-yry3tfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="p-yry3tfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:share-alt-square" {...props}></Icon>
