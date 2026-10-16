<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg95nlblw.css';
import '../../css/k/kbgev3boj.css';
import '../../css/i/ihmii9b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gg95nlblw"/><path class="kbgev3boj"/><path class="ihmii9b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:suction-bucket-48-bold" {...props}></Icon>
