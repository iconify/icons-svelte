<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqoigh7pk.css';
import '../../css/c/cwlq3hbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hqoigh7pk"/><path class="cwlq3hbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screwdriver-48-bold" {...props}></Icon>
