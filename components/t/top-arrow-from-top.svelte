<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb_xysb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb_xysb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:top-arrow-from-top" {...props}></Icon>
