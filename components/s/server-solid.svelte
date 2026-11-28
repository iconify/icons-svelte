<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw189cc1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw189cc1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:server-solid" {...props}></Icon>
