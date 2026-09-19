<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux6yzsbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux6yzsbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-08" {...props}></Icon>
