<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1xd6acdc.css';
import '../../css/q/q_650fa-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t1xd6acdc"/><path class="q_650fa-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-camera-20-bold" {...props}></Icon>
