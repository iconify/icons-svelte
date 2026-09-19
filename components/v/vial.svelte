<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt7_lq--z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt7_lq--z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vial" {...props}></Icon>
