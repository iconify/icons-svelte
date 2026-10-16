<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z46p_cexp.css';
import '../../css/k/k0mqbqbfv.css';
import '../../css/j/j2mvxkhzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z46p_cexp"/><path class="k0mqbqbfv"/><path class="j2mvxkhzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spray-can-48-bold" {...props}></Icon>
