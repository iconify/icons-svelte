<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfij42n3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rfij42n3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ticket-20-solid" {...props}></Icon>
