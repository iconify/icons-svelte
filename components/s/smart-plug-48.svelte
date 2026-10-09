<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4xw6ab6k.css';
import '../../css/w/waaecn3wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4xw6ab6k"/><path class="waaecn3wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-plug-48" {...props}></Icon>
