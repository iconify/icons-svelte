<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf6utcc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf6utcc_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:window-section" {...props}></Icon>
