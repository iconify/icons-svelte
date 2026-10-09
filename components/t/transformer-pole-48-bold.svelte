<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chivyabpi.css';
import '../../css/u/u7007_xth.css';
import '../../css/h/h_ntzgbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="chivyabpi"/><path class="u7007_xth"/><path class="h_ntzgbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transformer-pole-48-bold" {...props}></Icon>
