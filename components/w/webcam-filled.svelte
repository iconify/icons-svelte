<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz7555nvh.css';
import '../../css/q/q4tdn3ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz7555nvh"/><path class="q4tdn3ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:webcam-filled" {...props}></Icon>
