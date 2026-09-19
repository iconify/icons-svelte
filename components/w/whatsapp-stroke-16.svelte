<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-j-2kbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-j-2kbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:whatsapp-stroke-16" {...props}></Icon>
