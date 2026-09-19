<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xddonpb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xddonpb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:z2x-outline" {...props}></Icon>
