<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn83ztbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn83ztbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:zoom-in-thin" {...props}></Icon>
