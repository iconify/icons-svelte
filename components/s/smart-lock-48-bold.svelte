<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7x4xxw4v.css';
import '../../css/u/u0i-r0xuj.css';
import '../../css/k/kp3nk_bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j7x4xxw4v"/><path class="u0i-r0xuj"/><path class="kp3nk_bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-lock-48-bold" {...props}></Icon>
