<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lngiy9mxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lngiy9mxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:security-block" {...props}></Icon>
