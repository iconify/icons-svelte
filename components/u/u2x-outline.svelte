<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pits7kbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pits7kbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:u2x-outline" {...props}></Icon>
