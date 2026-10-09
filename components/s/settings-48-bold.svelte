<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mepm0bcky.css';
import '../../css/j/jsr_zti9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mepm0bcky"/><path class="jsr_zti9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settings-48-bold" {...props}></Icon>
