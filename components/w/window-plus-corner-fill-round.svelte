<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7--8bbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7--8bbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-plus-corner-fill-round" {...props}></Icon>
