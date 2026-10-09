<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf14hib5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mf14hib5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spring-48" {...props}></Icon>
