<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw937uq7x.css';
import '../../css/h/h8hd6s8wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sw937uq7x"/><path class="h8hd6s8wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tv-48-bold" {...props}></Icon>
