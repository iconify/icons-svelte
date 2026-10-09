<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3x9rfeak.css';
import '../../css/e/ebzb5lb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3x9rfeak"/><path class="ebzb5lb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thumbs-up-48-bold" {...props}></Icon>
