<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7-zclbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7-zclbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:stop-solid" {...props}></Icon>
