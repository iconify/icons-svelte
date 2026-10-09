<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rchvxnb6e.css';
import '../../css/i/i_vwc81mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rchvxnb6e"/><path class="i_vwc81mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spirit-level-48" {...props}></Icon>
