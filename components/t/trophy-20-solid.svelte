<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyheg1bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oyheg1bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:trophy-20-solid" {...props}></Icon>
