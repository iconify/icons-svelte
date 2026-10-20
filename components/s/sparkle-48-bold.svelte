<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnsb3bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fbnsb3bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkle-48-bold" {...props}></Icon>
