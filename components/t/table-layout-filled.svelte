<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we9t8-ysh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we9t8-ysh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-layout-filled" {...props}></Icon>
