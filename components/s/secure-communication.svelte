<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdwogh3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="omdwogh3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:secure-communication" {...props}></Icon>
