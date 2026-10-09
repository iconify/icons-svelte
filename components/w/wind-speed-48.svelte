<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oepi3hb8j.css';
import '../../css/m/mvcr2gb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oepi3hb8j"/><path class="mvcr2gb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-speed-48" {...props}></Icon>
