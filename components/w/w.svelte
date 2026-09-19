<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixb90tb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ixb90tb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:w" {...props}></Icon>
