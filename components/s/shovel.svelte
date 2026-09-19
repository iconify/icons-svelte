<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu70lnpid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu70lnpid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shovel" {...props}></Icon>
