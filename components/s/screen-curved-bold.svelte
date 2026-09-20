<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-4s82ben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-4s82ben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:screen-curved-bold" {...props}></Icon>
