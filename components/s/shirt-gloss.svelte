<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tghj5bcrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tghj5bcrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shirt-gloss" {...props}></Icon>
