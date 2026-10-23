<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue6qx8t1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue6qx8t1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wifi-low" {...props}></Icon>
