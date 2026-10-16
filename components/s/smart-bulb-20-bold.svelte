<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thnh47bcs.css';
import '../../css/f/fuhaovbal.css';
import '../../css/t/t1nxsq_lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thnh47bcs"/><path class="fuhaovbal"/><path class="t1nxsq_lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-bulb-20-bold" {...props}></Icon>
