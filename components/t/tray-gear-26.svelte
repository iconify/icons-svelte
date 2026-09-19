<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnfhi1qkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="cnfhi1qkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-gear-26" {...props}></Icon>
