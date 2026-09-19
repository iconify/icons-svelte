<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6oi_ibfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="p6oi_ibfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trash-20-solid" {...props}></Icon>
