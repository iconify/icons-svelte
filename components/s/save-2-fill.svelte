<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_wz2g67s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_wz2g67s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:save-2-fill" {...props}></Icon>
