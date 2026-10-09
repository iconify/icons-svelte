<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivpnqg4j.css';
import '../../css/p/pddr5rgfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="pddr5rgfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sidebar-20-bold" {...props}></Icon>
