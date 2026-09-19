<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcch-qbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vcch-qbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:share-20-solid" {...props}></Icon>
