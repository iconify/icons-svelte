<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-b8subje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-b8subje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:row-resize" {...props}></Icon>
