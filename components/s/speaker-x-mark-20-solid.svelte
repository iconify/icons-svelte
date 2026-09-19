<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3el5tocp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o3el5tocp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:speaker-x-mark-20-solid" {...props}></Icon>
