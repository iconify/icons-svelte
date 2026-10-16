<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc1420b7v.css';
import '../../css/t/tdu9i01lj.css';
import '../../css/o/onir-4bul.css';
import '../../css/m/mjlwt_b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fc1420b7v"/><path class="tdu9i01lj"/><path class="onir-4bul"/><path class="mjlwt_b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yaw-48-bold" {...props}></Icon>
