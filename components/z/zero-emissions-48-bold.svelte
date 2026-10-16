<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn7efoaca.css';
import '../../css/f/f56ez5bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cn7efoaca"/><path class="f56ez5bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zero-emissions-48-bold" {...props}></Icon>
