<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0l5ivb9x.css';
import '../../css/u/umgrjh4bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p0l5ivb9x"/><path class="umgrjh4bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:taco-48-bold" {...props}></Icon>
