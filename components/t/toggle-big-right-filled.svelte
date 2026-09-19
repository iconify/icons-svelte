<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzt74d93r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzt74d93r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggle-big-right-filled" {...props}></Icon>
