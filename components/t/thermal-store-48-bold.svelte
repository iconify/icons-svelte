<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epdku6b-c.css';
import '../../css/s/s7lyrq7xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="epdku6b-c"/><path class="s7lyrq7xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-store-48-bold" {...props}></Icon>
