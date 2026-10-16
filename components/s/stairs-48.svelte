<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjx5knxyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bjx5knxyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stairs-48" {...props}></Icon>
