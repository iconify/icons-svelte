<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/casto_bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="casto_bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:takeaway" {...props}></Icon>
