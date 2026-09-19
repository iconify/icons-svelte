<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhv4y6ces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhv4y6ces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tabs-filled" {...props}></Icon>
