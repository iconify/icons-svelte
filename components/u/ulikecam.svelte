<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx1xxj1an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rx1xxj1an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:ulikecam" {...props}></Icon>
