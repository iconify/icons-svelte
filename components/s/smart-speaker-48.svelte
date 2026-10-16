<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxwuhsbvz.css';
import '../../css/n/nif5jyb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vxwuhsbvz"/><path class="nif5jyb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-speaker-48" {...props}></Icon>
