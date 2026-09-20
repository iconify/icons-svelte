<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsx6tmbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsx6tmbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sxp" {...props}></Icon>
