<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8bn8bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8bn8bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:solid" {...props}></Icon>
