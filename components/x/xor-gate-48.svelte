<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdb70jjls.css';
import '../../css/n/n-cuddbov.css';
import '../../css/k/koaj76bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wdb70jjls"/><path class="n-cuddbov"/><path class="koaj76bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:xor-gate-48" {...props}></Icon>
