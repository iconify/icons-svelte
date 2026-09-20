<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udb7-vw_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udb7-vw_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:water" {...props}></Icon>
