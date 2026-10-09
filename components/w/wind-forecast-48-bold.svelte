<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwhfb7nyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mwhfb7nyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-forecast-48-bold" {...props}></Icon>
