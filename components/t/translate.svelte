<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esuc5dp6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esuc5dp6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:translate" {...props}></Icon>
