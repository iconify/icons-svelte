<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zisu_cc5g.css';
import '../../css/i/i8f0698ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zisu_cc5g"/><path class="i8f0698ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-rain-48-bold" {...props}></Icon>
