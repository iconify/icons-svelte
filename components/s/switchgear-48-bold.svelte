<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l79qy9iaa.css';
import '../../css/b/buu0taccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l79qy9iaa"/><path class="buu0taccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switchgear-48-bold" {...props}></Icon>
