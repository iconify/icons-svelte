<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5m3vuabl.css';
import '../../css/l/l0896yttc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a5m3vuabl"/><path class="l0896yttc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-low-20" {...props}></Icon>
