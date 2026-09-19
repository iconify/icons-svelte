<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r61xpml1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r61xpml1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:upload-thin" {...props}></Icon>
