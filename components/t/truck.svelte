<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdgd-5r7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdgd-5r7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:truck" {...props}></Icon>
