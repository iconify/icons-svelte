<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh4i5bm1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gh4i5bm1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:star-48" {...props}></Icon>
