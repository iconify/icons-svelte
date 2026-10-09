<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrqyz4i2u.css';
import '../../css/n/nx_frvvuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xrqyz4i2u"/><path class="nx_frvvuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shower-20" {...props}></Icon>
