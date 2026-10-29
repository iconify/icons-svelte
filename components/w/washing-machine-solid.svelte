<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz_7f5bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_7f5bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:washing-machine-solid" {...props}></Icon>
