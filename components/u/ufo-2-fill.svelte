<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjtde_bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjtde_bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ufo-2-fill" {...props}></Icon>
