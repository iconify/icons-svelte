<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp3sh4q-z.css';
import '../../css/c/co-d1_b7k.css';
import '../../css/t/tbph25zil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vp3sh4q-z"/><path class="co-d1_b7k"/><path class="tbph25zil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-sock-20" {...props}></Icon>
