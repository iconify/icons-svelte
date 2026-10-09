<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajs58j51b.css';
import '../../css/v/vh5d1qbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajs58j51b"/><path class="vh5d1qbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-asc-20" {...props}></Icon>
