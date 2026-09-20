<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coblflwkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coblflwkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ruler-2-fill" {...props}></Icon>
