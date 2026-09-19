<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg1pcqlsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cg1pcqlsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:x-outline" {...props}></Icon>
