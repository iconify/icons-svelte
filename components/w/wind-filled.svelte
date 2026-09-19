<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4dcqhbsd.css';
import '../../css/s/s-ajraboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4dcqhbsd"/><path class="s-ajraboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wind-filled" {...props}></Icon>
