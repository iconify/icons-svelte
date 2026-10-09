<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmxj-_ahy.css';
import '../../css/m/muoaj3btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmxj-_ahy"/><path class="muoaj3btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-stream-turbine-48-bold" {...props}></Icon>
