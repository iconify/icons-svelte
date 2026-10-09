<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uea8u9cfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uea8u9cfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storm-48-bold" {...props}></Icon>
