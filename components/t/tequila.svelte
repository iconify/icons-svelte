<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlq4-ewtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlq4-ewtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tequila" {...props}></Icon>
