<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9l9-clq.css';
import '../../css/y/yfq3bynsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx9l9-clq"/><path class="yfq3bynsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-bold-bold-duotone" {...props}></Icon>
