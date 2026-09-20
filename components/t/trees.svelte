<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhsf18bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhsf18bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:trees" {...props}></Icon>
