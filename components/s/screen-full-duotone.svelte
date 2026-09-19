<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeyf-3b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyf-3b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:screen-full-duotone" {...props}></Icon>
