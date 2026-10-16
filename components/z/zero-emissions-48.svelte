<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vek0mzq4d.css';
import '../../css/s/sf_tgu5lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vek0mzq4d"/><path class="sf_tgu5lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zero-emissions-48" {...props}></Icon>
